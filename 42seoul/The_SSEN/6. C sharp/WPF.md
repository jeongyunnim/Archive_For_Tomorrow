---
날짜: "2025-02-06"
넘버: 
태그: 프로그래밍/임베디드
출처: LIG Nex1 The SSEN Embedded SW School
강사: 김유진
aliases:
---
### 날짜:  2025-02-06 09:03

### 태그: #프로그래밍/임베디드

>[!메모]
>

### 원문
---
# WPF
- Windows Presentation Foundation
- 데스크톱 클라이언트 애플리케이션을 만드는 UI 프레임워크
- [[.NET]]의 일부
- XAML(Extensible Application markup Language)를 사용하여 애플리케이션 프로그래밍 을 위한 선언적 모델을 제공한다
	- XML: 디스크립션 표현, 데이터 표현
	- csv, json
	- UI에 필요한 구성요소를 모두 정의를 해놓았다.
- 이벤트 처리(로직)와 UI구성을 분리해놓았기 때문에 유지보수에 유리하다.
	- UI에서 이벤트가 발생하면 어떻게 처리하고 데이터를 표현할 것인지 
### WPF 환경 구성
- C#용 WPF
- 컨테이너
	- 패널: 윈도우에 배치할 수 있는 판을 두고 위젯을 놓을 수 있다.
		- 레이아웃 설계가 쉬워진다.
- 뷰 위젯
![[Pasted image 20250206092259.png]]
- 도구상자에서 위젯들을 가져다 놓을 수 있다.
- 요소를 더블클릭 시 해당 위젯에 대한 이벤트 핸들러를 제공해준다.
	- delegate로 이루어져 있다.
		- sender: 이벤트가 발생한 이벤트 객체
		- e: 이벤트의 종류, 위치 등 이벤트의 소스
```C#
private void btn1_Click(object sender, RoutedEventArgs e)
{
	Button btn = (Button)sender;
	MessageBox.Show(btn.Content.ToString());
}
```
![[Pasted image 20250206092920.png]]
Grid와 Stackpanel
- Text block
	- lable, 화면에 고정적으로 표시할 내용을 보여준다.
- TextBox
	- 입력 박스
- Text 값으로 출력할 메시지를 제어

### 데이터 표시하기
- 데이터를 표시할 객체는 public class로 정의해야 한다.
- C#적으로 표현하기
	- ToString 재정의
```C#
List<Person> listp = new List<Person>();
listp.Add(new Person("PersonA", 1));
listp.Add(new Person("PersonB", 5));
lst2.ItemsSource = listp;
```
- WPF 적으로 표현하는 방법
	- 데이터 바인딩
```xml
<ListBox x:Name="lst2" Height="100">
<ListBox.ItemTemplate>
    <DataTemplate>
        <Grid Margin="0,2">
            <Grid.ColumnDefinitions>
                <ColumnDefinition Width="50"/>
                <ColumnDefinition />
            </Grid.ColumnDefinitions>
            <TextBlock Text="{Binding Id}"/>
            <TextBlock Grid.Column="1" Text="{Binding Name}"/>
        </Grid>
    </DataTemplate>
</ListBox.ItemTemplate>
</ListBox>
```
![[Pasted image 20250206114708.png]]

### 재고 관리 예제

![[Pasted image 20250206153607.png]]

```xml
<Window x:Class="WpfApp2.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:WpfApp2"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <Grid>
        <Grid.ColumnDefinitions>
            <ColumnDefinition/>
            <ColumnDefinition/>
        </Grid.ColumnDefinitions>
        <StackPanel Grid.Column="0">
            <TextBlock x:Name="prodId" TextWrapping="Wrap" Text="Product Id" Height="50" FontSize="20"/>
            <TextBox x:Name="prodname" TextWrapping="Wrap" Text="name" Height="30" FontSize="15"/>
            <TextBox x:Name="prodprice" TextWrapping="Wrap" Text="price" Height="30" FontSize="15"/>
            <TextBox x:Name="prodamount" TextWrapping="Wrap" Text="amount" Height="30" FontSize="15"/>
            <Grid>
                <Grid.ColumnDefinitions>
                    <ColumnDefinition/>
                    <ColumnDefinition/>
                    <ColumnDefinition/>
                </Grid.ColumnDefinitions>
                <Button x:Name="addbtn" Content="추가" Margin="1,0,1,0" Height="20" VerticalAlignment="Top" Click="addbtn_Click"/>
                <Button x:Name="editbtn" Content="수정" Grid.Column="1" Margin="1,0,1,0" Click="editbtn_Click"/>
                <Button x:Name="delbtn" Content="삭제" Grid.Column="2" Margin="1,0,1,0" Click="delbtn_Click"/>
            </Grid>

        </StackPanel>
        <StackPanel Grid.Column="1">
            <TextBlock x:Name="listhead" TextWrapping="Wrap" Height="50" FontSize="20"><Run Language="ko-kr" Text="상품 목록"/></TextBlock>
            <Grid Margin="0,2" Background="#FFE6FFF9">
                <Grid.ColumnDefinitions>
                    <ColumnDefinition Width="50"/>
                    <ColumnDefinition Width="50"/>
                    <ColumnDefinition Width="50"/>
                    <ColumnDefinition Width="50"/>
                </Grid.ColumnDefinitions>
                <TextBlock Text="ID" FontWeight="Bold" TextAlignment="Center">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
                <TextBlock Grid.Column="1" Text="NAME" FontWeight="Bold" TextAlignment="Center">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
                <TextBlock Grid.Column="2" Text="PRICE" FontWeight="Bold" TextAlignment="Center">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
                <TextBlock Grid.Column="3" Text="AMOUNT" FontWeight="Bold" TextAlignment="Center" Margin="0,0,-10,0">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
            </Grid>
            <ListBox x:Name="prodlist" SelectionChanged="prodlist_SelectionChanged">
                <ListBox.ItemTemplate>
                    <DataTemplate>
                        <Grid Margin="0,2">
                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="50"/>
                                <ColumnDefinition Width="50"/>
                                <ColumnDefinition Width="50"/>
                                <ColumnDefinition Width="50"/>
                            </Grid.ColumnDefinitions>
                            <TextBlock Text="{Binding Id}"/>
                            <TextBlock Grid.Column="1" Text="{Binding Name}"/>
                            <TextBlock Grid.Column="2" Text="{Binding Amount}"/>
                            <TextBlock Grid.Column="3" Text="{Binding Price}"/>
                        </Grid>
                    </DataTemplate>
                </ListBox.ItemTemplate>
            </ListBox>
        </StackPanel>
    </Grid>
</Window>

```

```c#
using System.Text;
using System.Windows;
using System.Windows.Controls;
using System.Windows.Data;
using System.Windows.Documents;
using System.Windows.Input;
using System.Windows.Media;
using System.Windows.Media.Imaging;
using System.Windows.Navigation;
using System.Windows.Shapes;
using static System.Net.Mime.MediaTypeNames;

namespace WpfApp2
{
    /// <summary>
    /// Interaction logic for MainWindow.xaml
    /// </summary>
    public partial class MainWindow : Window
    {
        List<Product> list = new List<Product>();
        public MainWindow()
        {
            InitializeComponent();
            prodlist.ItemsSource = list;
        }

        private void addbtn_Click(object sender, RoutedEventArgs e)
        {
            try
            {
                list.Add(new Product(prodname.Text, Int32.Parse(prodprice.Text), Int32.Parse(prodamount.Text)));
                prodlist.Items.Refresh();
            }
            catch (Exception exc)
            {
                MessageBox.Show("Error: 잘못된 입력입니다.");
            }
        }

        private void prodlist_SelectionChanged(object sender, SelectionChangedEventArgs e)
        {
            ListBox selected = (ListBox)sender;
            int idx = selected.SelectedIndex;

            if (idx == -1)
                return;
            Product find = list[idx];
            prodId.Text = find.Id.ToString();
            prodname.Text = find.Name;
            prodprice.Text = find.Price.ToString();
            prodamount.Text = find.Amount.ToString();
        }

        private void editbtn_Click(object sender, RoutedEventArgs e)
        {
            int price, amount;
            int idx = prodlist.SelectedIndex;
            
            if (idx == -1)
            {
                MessageBox.Show("Error: 잘못된 접근입니다.");
                return;
            }
            Product find = list[idx];
            try
            {
                amount = Int32.Parse(prodamount.Text);
                price = Int32.Parse(prodprice.Text);
            }
            catch
            {
                MessageBox.Show("Error: 잘못된 입력입니다.");
                return;
            }
            find.Name = prodname.Text;
            find.Price = price;
            find.Amount = amount;
            prodlist.Items.Refresh();
        }

        private void delbtn_Click(object sender, RoutedEventArgs e)
        {
            int idx = prodlist.SelectedIndex;
            
            if (idx == -1)
            {
                MessageBox.Show("Error: 잘못된 접근입니다.");
                return;
            }
            list.RemoveAt(idx);
            prodlist.Items.Refresh();
        }
    }

    public class Product
    {
        public int Id { get; set; }
        public string Name { get; set; }
        public int Price { get; set; }
        public int Amount { get; set; }
        private static int idPool = 10000;
        public Product(string name, int price, int amount)
        {
            Id = idPool++;
            Name = name;
            Price = price;
            Amount = amount;
        }

        public Product(int id)
        {
            Id = id;
        }
        public override bool Equals(object? obj)
        {
            if (obj == null || obj is not Product)
                return false;
            return Id == ((Product)obj).Id;
        }
    }
}
```

### MVC
- model(데이터) / view(뷰) / controller(흐름제어)
	- 데이터의 이동이 너무 많이 일어나는 문제가 일어났다.
### MVVM
- model / view model(뷰와 데이터 사이에서 기능 처리, 이벤트를 중심으로) / view
- view 에서 표현하려는 데이터, 데이터를 저장해줄 모델을 정의한다.
- 모델
	- INotifyPropertyChanged를 상속 받는다.
	- 속성 변경을 알리도록 하는 인터페이스
	- 각각의 속성이 변경이 되었을 때 감지를 해서 이벤트를 트리거 해준다.
- 발생한 변경을 감지하고 속성의 이름을 받아 핸들러를..
```C#
 public event PropertyChangedEventHandler PropertyChanged;
 protected void onPropertyChanged(string propertyName)
 {
	 PropertyChangedEventHandler handler = PropertyChanged;
	 if(handler != null) handler(this, new PropertyChangedEventArgs(propertyName));
 }
```
- 모델 작성
	- **public 으로 작성해야 한다.** 외부에서 접근이 안된다.
- 뷰모델 작성
- 뷰모델 뷰에 추가
	- DataContext="ViewModel.MainWindowViewModel"

- 옵저버...


- 위젯에 표시할(연결할_ 데이터를 모델에 저장.
	- 변화를 감시할 데이터를 이벤트에 등록을 해준다.
- `{Binding Model.Num}`
	- 뷰 모델의 값

### Command 클래스 추가
- click 이벤트 handler 대신 Command를 사용한다.
	- `Command="Binding CMD"`
- 어떤 이벤트가 트리거 됐을 때 어떤 동작을 할 것인가
- 정상적인 상황인지 아닌지 체크하는 CanExcute
	- 명령 객체를 인자로 받는다.
- Execute
	- 이벤트 발생 시 실행할 함수
- viewmodel에 cmd 객체 생성
```C#
public class Command : ICommand
{
	Action<object> _execute;
	Func<object, bool> _executeFunc;

	public Command(Action<object> execute, Func<object, bool> executeFunc)
	{
		_execute = execute;
		_executeFunc = executeFunc;
	}

	public event EventHandler? CanExecuteChanged;

	public bool CanExecute(object? parameter)
	{
		return _executeFunc(parameter);
	}

	public void Execute(object? parameter)
	{
		_execute(parameter);
	}
}
```
- 모델 객체에 Res 멤버변수 추가
### List로 관리하기
```C#
private List<Person> persons;
public List<Person> Persons
{
	get { return persons; }
}

private Command cmdPerson;
public Command CmdPerson
{
	get; set;
}
public MainWindowViewModel()
{
	model = new MainWindowModel();
	Cmd = new Command(execute, canExecute);
	CmdPerson = new Command(executePerson, canExecute);
	persons = new List<Person>();
	persons.Add(new Person(1001, "코코"));
	persons.Add(new Person(1002, "코리"));
	persons.Add(new Person(1003, "코삼"));
}
public void executePerson(object obj)
{
	persons.Add(new Person(Model.Num, Model.Name));
	onPropertyChanged("Persons");
}
```
### Observable
- List 내부의 객체 변경은 List가 아니라 감지가 불가
```C#
public void executeEdit(object obj)
{
	MessageBox.Show("selected: " + P.ToString());

	P.Num = Model.Num;
	// 바뀌지 않는다. -> Observer는 이미 있는 객체에 대한 이벤트를 감지하지 않는다.
	P.Name = Model.Name; 
}
```
- Person객체 또한 INotifyProperty를 통해 감시하도록 해야 한다.
	- Person의 각 요소를 Binding 해주어야 변경 시 반영이 된다.

- [ ] 변수에 대한 접근 축약과 명시 차이
	- `{ get; }`은 동작 안 함.
	- `{ get { return list; } }`는 동작함.
### behaviors
- 이벤트를 트리거하고 핸들러를 바인딩할 수 있도록 도와주는 NuGet 패키지
### 물류관리 프로그램 MVVM 패턴 적용
![[Pasted image 20250207191452.png]]
### MainWindow.xaml
```xml
<Window x:Class="ProductProgramUI.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:ProductProgramUI" 
        xmlns:Behaviors="http://schemas.microsoft.com/xaml/behaviors"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <Grid>
        <Grid.ColumnDefinitions>
            <ColumnDefinition/>
            <ColumnDefinition/>
        </Grid.ColumnDefinitions>
        <StackPanel Grid.Column="0">
            <TextBlock x:Name="prodId" TextWrapping="Wrap" Text="{Binding Model.Id}" Height="50" FontSize="20"/>
            <TextBox x:Name="prodname" TextWrapping="Wrap" Text="{Binding Model.Name}" Height="30" FontSize="15"/>
            <TextBox x:Name="prodprice" TextWrapping="Wrap" Text="{Binding Model.Price}" Height="30" FontSize="15"/>
            <TextBox x:Name="prodamount" TextWrapping="Wrap" Text="{Binding Model.Amount}" Height="30" FontSize="15"/>
            <Grid>
                <Grid.ColumnDefinitions>
                    <ColumnDefinition/>
                    <ColumnDefinition/>
                    <ColumnDefinition/>
                </Grid.ColumnDefinitions>
                <Button x:Name="addbtn" Content="추가" Margin="1,0,1,0" Height="20" VerticalAlignment="Top" Command="{Binding CmdAdd}"/>
                <Button x:Name="editbtn" Content="수정" Grid.Column="1" Margin="1,0,1,0" Command="{Binding CmdEdit}"/>
                <Button x:Name="delbtn" Content="삭제" Grid.Column="2" Margin="1,0,1,0" Command="{Binding CmdDel}"/>
            </Grid>

        </StackPanel>
        <StackPanel Grid.Column="1">
            <TextBlock x:Name="listhead" TextWrapping="Wrap" Height="50" FontSize="20"><Run Language="ko-kr" Text="상품 목록"/></TextBlock>
            <Grid Margin="20,2,20,2" Background="#FFE6FFF9">
                <Grid.ColumnDefinitions>
                    <ColumnDefinition Width="50"/>
                    <ColumnDefinition Width="50"/>
                    <ColumnDefinition Width="50"/>
                    <ColumnDefinition Width="50"/>
                </Grid.ColumnDefinitions>
                <TextBlock Text="ID" FontWeight="Bold" TextAlignment="Center">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
                <TextBlock Grid.Column="1" Text="NAME" FontWeight="Bold" TextAlignment="Center">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
                <TextBlock Grid.Column="2" Text="PRICE" FontWeight="Bold" TextAlignment="Center">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
                <TextBlock Grid.Column="3" Text="AMOUNT" FontWeight="Bold" TextAlignment="Center" Margin="0,0,-10,0">
                    <TextBlock.OpacityMask>
                        <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                            <GradientStop Color="Black"/>
                            <GradientStop Color="White" Offset="1"/>
                        </LinearGradientBrush>
                    </TextBlock.OpacityMask>
                </TextBlock>
            </Grid>
            <ListBox x:Name="prodlist" SelectedItem="{Binding P}" ItemsSource="{Binding Products}" SelectedIndex="{Binding SelectedIdx}" d:ItemsSource="{d:SampleData ItemCount=5}" Margin="20,0,20,0" Height="209">
                <Behaviors:Interaction.Triggers>
                    <Behaviors:EventTrigger EventName="SelectionChanged">
                        <Behaviors:InvokeCommandAction Command="{Binding CmdSel}"/>
                    </Behaviors:EventTrigger>
                </Behaviors:Interaction.Triggers>
                <ListBox.ItemTemplate>
                    <DataTemplate>
                        <Grid Margin="0,2">
                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="50"/>
                                <ColumnDefinition Width="50"/>
                                <ColumnDefinition Width="50"/>
                                <ColumnDefinition Width="50"/>
                            </Grid.ColumnDefinitions>
                            <TextBlock Text="{Binding Id}"/>
                            <TextBlock Grid.Column="1" Text="{Binding Name}"/>
                            <TextBlock Grid.Column="2" Text="{Binding Amount}"/>
                            <TextBlock Grid.Column="3" Text="{Binding Price}"/>
                        </Grid>
                    </DataTemplate>
                </ListBox.ItemTemplate>
            </ListBox>
        </StackPanel>
    </Grid>
</Window>
```
### MainWindow.cs
- DataContext를 연결해준다.
```c#
DataContext = new ProductProgramUI.ViewModel.MainViewModel();
```
### Model.MainWinModel
- 화면에 표시할 데이터와 연결할 모델 객체
```c#
namespace ProductProgramUI
{
    public class Command : ICommand
    {
        Action<object> _execute;
        Func<object, bool> _executeFunc;

        public Command(Action<object> execute, Func<object, bool> executeFunc)
        {
            _execute = execute;
            _executeFunc = executeFunc;
        }

        public event EventHandler? CanExecuteChanged;

        public bool CanExecute(object? parameter)
        {
            return _executeFunc(parameter);
        }

        public void Execute(object? parameter)
        {
            _execute(parameter);
        }
    }
}
```
### Model.Product
- 물류의 정보를 저장할 Product 객체
```c#
namespace ProductProgramUI.Model
{
    public class Product : INotifyPropertyChanged
    {
        private static int idPool = 10000;
        private int id;
        public int Id 
        {
            get { return id; }
            set { id = value;  onPropertyChanged("Id"); }
        }

        private string name;
        public string Name
        {
            get { return name; }
            set { name = value; onPropertyChanged("Name"); }
        }
        public int price;
        public int Price
        {
            get { return price; }
            set { price = value; onPropertyChanged("Price"); }
        }
        public int amount;
        public int Amount
        {
            get { return amount; }
            set { amount = value; onPropertyChanged("Amount"); }
        }

        public Product(string name, int price, int amount)
        {
            Id = idPool++;
            Name = name;
            Price = price;
            Amount = amount;
        }

        public event PropertyChangedEventHandler? PropertyChanged;
        protected void onPropertyChanged(string propertyName)
        {
            PropertyChangedEventHandler handler = PropertyChanged;
            if (handler != null)
                handler(this, new PropertyChangedEventArgs(propertyName));
        }
    }
}

```
### ViewModel.MainViewModel
- 뷰와 모델을 연결하는 ViewModel 객체
```C#
namespace ProductProgramUI.ViewModel
{
    public class MainViewModel : INotifyPropertyChanged
    {
        private MainWinModel model;
        public MainWinModel Model
        {
            get { return model; }
            set { model = value; onPropertyChanged("Model"); }
        }
        private ObservableCollection<Product> products;
        public ObservableCollection<Product> Products
        {
            get { return products; }
        }
        public int SelectedIdx
        { get; set; }
        
        public Product P
        { get; set; }

        public Command CmdAdd
        { get; set; }

        public Command CmdEdit
        { get; set; }

        public Command CmdDel
        { get; set; }
        public Command CmdSel
        { get; set; }

        public MainViewModel()
        {
            model = new MainWinModel();
            CmdAdd = new Command(executeAdd, checkEmpty);
            CmdEdit = new Command(executeEdit, checkIdx);
            CmdDel = new Command(executeDel, checkIdx);
            CmdSel = new Command(executeSel, checkIdx);
            products = new ObservableCollection<Product>();
            products.Add(new Product("ex", 1000, 50));
        }

        public void executeSel(object obj)
        {
            Model.Id = P.Id;
            Model.Name = P.Name;
            Model.Amount = P.Amount;
            Model.Price = P.Price;
        }

        public void executeAdd(object obj)
        {
            products.Add(new Product(Model.Name, Model.price, Model.Amount));
        }

        public void executeDel(object obj)
        {
            products.RemoveAt(SelectedIdx);
        }

        public void executeEdit(object obj)
        {
            P.Name = Model.Name;
            P.Amount = Model.Amount;
            P.Price = Model.Price;
        }

        public bool canExecute(object obj)
        {
            return true;
        }

        public bool checkIdx(object obj)
        {
            if (SelectedIdx < 0)
            {
                return false;
            }
            return true;
        }

        public bool checkEmpty(object obj)
        {
            if (Model.Name.Length == 0)
            {
                MessageBox.Show("내용을 입력해주세요");
                return false;
            }
            return true;
        }

        public event PropertyChangedEventHandler? PropertyChanged;
        protected void onPropertyChanged(string propertyName)
        {
            PropertyChangedEventHandler handler = PropertyChanged;
            if (handler != null)
                handler(this, new PropertyChangedEventArgs(propertyName));
        }
    }
}

```
---
### 생각(파생된 질문/생각)

### 출처
- LIG Nex1 The SSEN Embedded SW School

### 연결 문서 (연결 이유)
