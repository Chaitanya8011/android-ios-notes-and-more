Project to make for practice  links-

1.Crud App FireBase -  Store, Retrieve, Search, Delete and Update Data using Firebase Realtime Database in Android Studio



2 - Shoe CartApplication
Shoe App ( Cart Management with Local DB) -  ( EXECUTORS , MVVM and ROOM )



3.To Do List App Introduction ( Using Sqlite DataBase 2020 )



Component practice reamin
1.constraint layout
2.recycler view
2.list view
3.onbindView
4.Adapter

Chaitanya  mahesh gondkar  - (Android Development)
1.coffeShop project on android studio in this  we did
Fragment tutorial 

27/12/2024
     
	1. Make to do app
	2. Learn layouts … 
	3. View in android
	4. Learn ui
	5. Intent,fragment,bundle
	6. Learn types of  layouts in android
	7. lists

Roadmap to learn Android App Development
	• Programming
		○ Java
		○ Kotlin
		○ 
	• 3rd Party Library
		○ Image Loading
			§ Glide
			§ Picasso
		○ Dependency Injection
			§ Dagger
		○ Networking
			§ Fast Android Networking Library
			§ Retrofit
		○ MultiThreading
			§ RxJava
			§ Coroutines
			§ Kotlin Flow API
	• Coroutines - You can learn these topics here: Master Kotlin Coroutines
		○ coroutines
		○ suspend
		○ launch, async-await, withContext
		○ dispatchers
		○ scope, context, job
		○ lifecycleScope, viewModelScope, GlobalScope
		○ suspendCoroutine, suspendCancellableCoroutine
		○ coroutineScope, supervisorScope
	• Kotlin Flow API - You can learn these topics here: Kotlin Flow API
		○ Flow Builder, Operator, Collector
		○ flowOn, dispatchers
		○ Operators such as filter, map, zip, flatMapConcat, retry, debounce, distinctUntilChanged, flatMapLatest
		○ Terminal operators
		○ Cold Flow vs Hot Flow: Cold Flow vs Hot Flow
		○ StateFlow, SharedFlow, callbackFlow, channelFlow
	• Data Format
		○ JSON
			§ GSON
		○ Flat Buffer
		○ Protocol Buffer
	• Networking
		○ GET/POST/DELETE/PUT/PATCH
		○ OkHttp, Interceptor
		○ Caching
		○ Retrofit with Coroutines/Flow
		○ Multipart request
		○ Read, Write Timeout
		○ OAuth 2.0 - Refresh and Access Token
		○ HTTP Status Codes
	• Android Jetpack
		○ Foundation Components
			§ AppCompat
			§ Android KTX
			§ Multidex
		○ Architecture Components
			§ LiveData
			§ ViewModel
			§ DataBinding
			§ Paging
			§ Work Manager
			§ Navigation
		○ Behaviour Components
			§ Download Manager
			§ Media Playback
			§ Notification
			§ Permissions
			§ Preference
			§ Sharing
			§ Slice
		○ UI Component
			§ Animation & Transition
			§ Android Auto
			§ Emoji
			§ Palette
			§ Android TV
			§ Android Wear
	• Compose
		○ State: remember, rememberSaveable, MutableState
		○ Recomposition
		○ State hoisting
		○ Side-effects
		○ Modifier
		○ Theme
		○ Layout, List
		○ Gestures, Animation
		○ CompositionLocal
	• Common Design Patterns and Architecture
		○ Builder Pattern
		○ Singleton
		○ Dependency Injection
		○ Factory
		○ Observer
		○ Repository
		○ MVVM
		○ MVP
		○ MVI
		○ Clean architecture
	• Unit Testing
		○ Local Unit Testing
		○ Instrumentation Testing
	• Firebase
		○ FCM
		○ Crashlytics
		○ Analytics
		○ Remote Config
		○ App Indexing
		○ Dynamic Link
	• Security
		○ Encrypt / Decrypt
		○ Proguard
		○ R8
	• App Release
		○ .keystore file
		○ App Bundle
		○ Playstore
	• Keep Learning
	• Android Studio
		○ Android Studio IDE Overview
		○ Project Structure
			§ Java/Kotlin
			§ XML
			§ .gradle files
	• Android Component
		○ Activity
			§ Activity Lifecycle
			§ Tasks & Back Stack
		○ Service
		○ Broadcast Receiver
		○ Content Provider
	• Intents
		○ Types of Intent
			§ Implicit
			§ Explicit
		○ Intent Filter
	• Static User Interface
		○ View
			§ Button, ImageView, TextView, EditText etc
		○ ViewGroup
			§ LinearLayout, RelativeLayout, FrameLayout, ConstraintLayout
	• Dynamic User Interface
		○ RecyclerView
		○ ViewPager
		○ Spinner
	• CustomView
		○ Canvas
		○ Bitmap
		○ Paint
	• UI Resources
		○ Drawables
		○ String
		○ Styles
	• Fragments
		○ Fragment Lifecycle
		○ Fragment Manager
	• Support User Interface
		○ ProgressBar
		○ Dialogs
		○ Toast & Snackbar
	• Storage
		○ Shared Preferences
		○ DataStore
		○ File Systems
		○ Database
			§ RoomDB
	• Build
		○ Gradle
		○ Debug / Release Configuration
	• Threading
		○ Thread
		○ Handler/Looper
		○ ThreadPoolExecutor
		○ RxJava
		○ Coroutines/Flow
		○ WorkManager
	• Debugging
		○ Memory profiling
		○ Logging
		○ Systrace
		○ Exceptions
		○ Error Handling
	• Memory Leak
		○ Detecting and Fixing Memory Leaks
		○ Context and Improving

28/12/2024  - class notes

1.MAM made todo list with sql lite database          

 RoomDB to App - 
 1. Add the dependency, app's build.gradle,
 under dependencies section implementation("androidx.room:room-runtime:2.6.1") annotationProcessor("androidx.room:room-compiler:2.6.1") 
2. Annotate your bean/model with @Entity, @PrimaryKey (autoGenerate=true) 
3. DAO interface- with @Insert, @Query, @Update, @Delete
 4. AppDatabase

5e9ad8ca216649e1996b388dd5ee97d0

From <https://newsapi.org/register/success> 

https://newsapi.org/v2/everything?q=keyword&apiKey=5e9ad8ca216649e1996b388dd5ee97d0

54d19b247ee4f36e82a8b0ff3a961ef9 -open weather api key

pub_65800517779116987d6ff4fcef26c33cf1ca9 - newa PI KEY


Travel_Api

https://api.aviationstack.com/v1/flights?access_key=3de2f0ad8bd326e1426234de8fd8705c

https://jsonplaceholder.typicode.com/users  - user api

https://jsonplaceholder.typicode.com/users -free use link

//packagecom.example.mymovieapp_two.Model.Ui
//
//importandroid.os.Bundle
//importandroidx.fragment.app.Fragment
//importandroid.view.LayoutInflater
//importandroid.view.View
//importandroid.view.ViewGroup
//importandroidx.navigation.fragment.findNavController
//importandroidx.recyclerview.widget.LinearLayoutManager
//importandroidx.recyclerview.widget.RecyclerView
//importcom.example.mymovieapp_two.Model.Adapter.MovieAdapter
//importcom.example.mymovieapp_two.Model.Model.Movie
//importcom.example.mymovieapp_two.Model.Service.MovieApi
//importcom.example.mymovieapp_two.R
//importretrofit2.Call
//importretrofit2.Callback
//importretrofit2.Response
//
//
//classMovieListFragment:Fragment(){
//privatelateinitvarrecyclerView:RecyclerView
//privatevarmovieapi=MovieApi.create()
//
//overridefunonCreateView(
//inflater:LayoutInflater,container:ViewGroup?,
//savedInstanceState:Bundle?
//):View?{
//valview=inflater.inflate(R.layout.fragment_movie_list,container,false)
//
//recyclerView=view.findViewById(R.id.recyclerview)
//recyclerView.layoutManager=LinearLayoutManager(requireContext())
//fetchMovies()
//returnview
//}
//
//privatefunfetchMovies(){
//
//movieapi.GetallData("tt3896198","f66c290e").enqueue(object:Callback<Movie>{
//overridefunonResponse(call:Call<Movie>
//,response:Response<Movie>){
//if(response.isSuccessful)
//{
//valMovies=response.body()?.imdbID?.isEmpty()
//recyclerView.adapter=MovieAdapter(Movies){selectedMovie->
//valaction=MovieListFragmentDirections.actionMovieListFragmentToMovieDetailFragment(selectedMovie)
//findNavController().navigate(action)
//}
//}
//}
//
//overridefunonFailure(call:Call<Movie>,t:Throwable){
//}
//
//})
//
//
//
//
//
//}
//

View model
Dagger
hilt

packagecom.example.mileston_assesment2_chaitanyagondkar.UI

importandroid.os.Bundle
importandroidx.fragment.app.Fragment
importandroid.view.LayoutInflater
importandroid.view.View
importandroid.view.ViewGroup
importandroid.widget.Button
importandroid.widget.TextView
importandroid.widget.Toast
importandroidx.navigation.fragment.findNavController
importcom.example.mileston_assesment2_chaitanyagondkar.Model.WeatherModel
importcom.example.mileston_assesment2_chaitanyagondkar.R
importcom.example.mileston_assesment2_chaitanyagondkar.Serevice.RetrFitInstance
importretrofit2.Call
importretrofit2.Callback
importretrofit2.Response


classMainFragment:Fragment(){


overridefunonCreateView(
inflater:LayoutInflater,container:ViewGroup?,
savedInstanceState:Bundle?
):View?{
//Inflatethelayoutforthisfragment
valview=inflater.inflate(R.layout.fragment_main,container,false)
valtexts=view.findViewById<TextView>(R.id.texttt)
valButton=view.findViewById<Button>(R.id.button)
Button.setOnClickListener(fetchdata())
returnview
}

privatefunfetchdata(){
TODO("Notyetimplemented")
RetrFitInstance.api.getalldata("2fd5425d8ce909772fc8120bb45f3b01","city").enqueue(object:Callback<WeatherModel>{

overridefunonResponse(
call:Call<WeatherModel>,
response:Response<WeatherModel>
){
if(response.isSuccessful){
valdetails=response.body()
MainFragmentDirections.actionMainFragmentToDetailFragment(details)
findNavController().navigate(details)
}
else
{

Toast.makeText(requireContext()."failedtofetrch",Toast.LENGTH_SHORT).Show()


}

overridefunonFailure(call:Call<WeatherModel>,t:Throwable){


Toast.makeText(requireContext(),"${t.message}",Toast.LENGTH_SHORT).show()
}

}
})










}

}


import java.util.List;
import java.util.ArrayList;

public class Main
{
	public static void main(String[] args) {
	    
	    List<Integer> list = new ArrayList<>();
	    list.add(10);
	    list.add(20);
	    list.add(30);
	    list.add(40);
	    list.add(50);
	    System.out.println(list);
	    	    List<Integer> nlist = new ArrayList<>();
        nlist.add(56);
	    nlist.add(70);
	    nlist.add(80);
	    System.out.println(nlist);
	    nlist.addAll(list);
	    	    System.out.println(nlist);
	    	    	    	    System.out.println(nlist.get(1));
           nlist.remove(1);
	    	    System.out.println(nlist);
	    	    nlist.remove(Integer.valueOf(80));
	    	    	    	    System.out.println(nlist);
	    	    	    	            //   nlist.clear();
	    	    	    	            //   	    	    System.out.println(nlist);
	    	    	    	            nlist.set(1,45);
	    	    	    	            	    	    	    	    System.out.println(nlist);


	    	    	    	               






	    
	}
}

22-1-2025




// var chaitanya = "cmg"
// print(chaitanya)
// var chaotanya:String = "cmghdhd"
// print(chaotanya)
// var dobby = 120.2
// var a = chaitanya + String(dobby)
// print(a)
// print("value of double is = \(dobby) ")
// print("let equation 6*9 is \(6*9) is not 42!")
// let myarr = ["chaitanya","shradha","ketaki","yasheee",]
// let secondelement = myarr[3]
// print(secondelement)
// var mutablelist = myarr
// mutablelist[2]="pillya"
// print(mutablelist)
// let emptyarray = Array<String>()
// var someoptional:String? = "haromine"
// var sumnum = 4
// if let num =sumnum , num>1
// {
//   print("you can do it chaiyanya")
// }
let someNumber: Int? = 7
if let num = someNumber, num > 3 {
    print("num is not nil and is greater than 3")
}
let hunter:Int?=5
if let num = hunter,num>2
{
  print("chaitanya you can do it")
}

28/1/2025




Bank Account and Savings Account Classes
You are building a banking application. The BankAccount class has basic account details like balance and a method deposit(). The SavingsAccount class inherits from BankAccount and adds a property interestRate and a method to calculate interest.
	• How would you implement inheritance in this scenario?
	• Create a function in the SavingsAccount class to calculate and display the interest based on the current balance.

Ans - >

Closure- 26/1/2025 swift practice

// var greetings="hello iam chaitanya gondkar"
// greetings = " "
//  print(greetings)
//  var closure : (() -> Void)
//  func getData(param:Int)
// {
 // }

// func ParameterFunc(param:(() -> String))
// {
//       print(param())
// }
// ParameterFunc{
//   return "heyy gys"
// }

// func shows(name:(()-> String)){  print(name())}
// shows{
//   return "chaitnay "
// }

func showData(param:((String) -> String))
{       let c = "chaitanya"
       print(param(c))
}
showData { Stringval in 
  return Stringval + "hello ji"

}




func shows(param:((String)->String))
{
  let Hi = "Chaitanya"
   print(param(Hi))
}
shows{sub in
  return sub +  "you can do any thing jo bhi chahu wo mein pau jindaggi mein jit jau ba sitnsa khha b hain"
}







Employee and Manager Class
You are building an employee management system. You have an Employee class that holds basic employee details such as name, id, and salary. You also need to create a Manager class that inherits from Employee, with additional properties like department and teamSize.
	• How would you design these classes using inheritance in Swift?
	• Implement a function in the Manager class to print the details of the manager, including the department and team size.
	•  
	// Base class
	class Employee {
	    var name: String
	    var id: Int
	    var salary: Double
	
	    init(name: String, id: Int, salary: Double) {
	        self.name = name
	        self.id = id
	        self.salary = salary
	    }
	
	    func displayDetails() {
	        print("Employee Name: \(name), ID: \(id), Salary: \(salary)")
	    }
	}
	
	// Subclass
	class Manager: Employee {
	    var department: String
	    var teamSize: Int
	
	    init(name: String, id: Int, salary: Double, department: String, teamSize: Int) {
	        self.department = department
	        self.teamSize = teamSize
	        super.init(name: name, id: id, salary: salary)
	    }
	
	    func displayManagerDetails() {
	        super.displayDetails() // Call the base class method
	        print("Department: \(department), Team Size: \(teamSize)")
	    }
	}
	
	// Example usage
	let manager = Manager(name: "John Doe", id: 101, salary: 75000, department: "Engineering", teamSize: 8)
	manager.displayManagerDetails()
	

Optionals-



Swift

class BankAccount {
    var accountNumber: String
    var accountHolderName: String
    var balance: Double
    
    init(accountNumber: String, accountHolderName: String, initialBalance: Double) {
        self.accountNumber = accountNumber
        self.accountHolderName = accountHolderName
        self.balance = initialBalance
    }
    
    func deposit(amount: Double) {
        balance += amount
        print("Deposited \(amount). New balance: \(balance)")
    }
    
    func withdraw(amount: Double) {
        if amount > balance {
            print("Insufficient funds. Current balance: \(balance)")
        } else {
            balance -= amount
            print("Withdrew \(amount). New balance: \(balance)")
        }
    }
    
    func displayBalance() {
        print("Account Number: \(accountNumber) | Account Holder: \(accountHolderName) | Balance: \(balance)")
    }
    
    func transfer(amount: Double, to recipient: BankAccount) {
        if amount > balance {
            print("Transfer failed. Insufficient balance.")
        } else {
            withdraw(amount: amount)
            recipient.deposit(amount: amount)
            print("Transferred \(amount) from \(accountNumber) to \(recipient.accountNumber).")
        }
    }
}
// Example usage:
let account1 = BankAccount(accountNumber: "7864", accountHolderName: "chaitanya", initialBalance: 1000)
let account2 = BankAccount(accountNumber: "8567", accountHolderName: "wipro", initialBalance: 500)
account1.deposit(amount: 200)
account1.withdraw(amount: 300)
account1.displayBalance()
account1.transfer(amount: 400, to: account2)
account1.displayBalance()


Question:Implement a ShoppingCart class in Swift. It should: Contain an array of Product objects. Allow adding and removing products from the cart. Calculate the total cost of the items in the cart.
Ans. - >

// Product class
class Product {
    let name: String
    let price: Double
    
    init(name: String, price: Double) {
        self.name = name
        self.price = price
    }
}
// ShoppingCart class
class ShoppingCart {
    private var products: [Product] = []
        func addProduct(_ product: Product) {
        products.append(product)
    }
    func removeProduct(_ product: Product) {
        products.removeAll { $0.name == product.name }
    }
    
    // Calculate total cost
    func calculateTotalCost() -> Double {
        return products.reduce(0) { $0 + $1.price }
    }
    
    // Display cart contents
    func displayCart() {
        print("Cart Contents:")
        for product in products {
            print("-prodcut name rs  = \(product.name): and price is rs\(product.price)")
        }
        print("Total amoubnt: rs\(calculateTotalCost())")
    }
}
// Example usage
let apple = Product(name: "bokok", price: 100)
let banana = Product(name: "plates", price: 545)
let cart = ShoppingCart()
cart.addProduct(apple)
cart.addProduct(banana)
cart.displayCart()
cart.removeProduct(banana)
cart.displayCart()


Q.

Question:Create a Task class to manage tasks in a task management system. Each task should have:
	• A taskName and dueDate.
	• A method to mark the task as completed.
	• A method to check if the task is overdue (i.e., if the dueDate has passed)
	• Ans - >
     



Bank Account and Savings Account Classes
You are building a banking application. The BankAccount class has basic account details like balance and a method deposit(). The SavingsAccount class inherits from BankAccount and adds a property interestRate and a method to calculate interest.
	• How would you implement inheritance in this scenario?
	• Create a function in the SavingsAccount class to calculate and display the interest based on the current balance.
	
	import Foundation
	class Task {
	    var taskName: String
	    var dueDate: Date
	    var isCompleted: Bool = false
	    init(taskName: String, dueDate: Date) {
	        self.taskName = taskName
	        self.dueDate = dueDate
	    }
	    func markAsCompleted() {
	        isCompleted = true
	    }
	    func isOverdue() -> Bool {
	        return Date() > dueDate && !isCompleted
	    }
	}
	// Example usage
	let formatter = DateFormatter()
	formatter.dateFormat = "yyyy-MM-dd"
	// Create tasks
	if let gamingDueDate = formatter.date(from: "2025-01-25"),
	   let codingDueDate = formatter.date(from: "2025-01-20") {
	    let gamingTask = Task(taskName: "Gaming", dueDate: gamingDueDate)
	    let codingTask = Task(taskName: "Coding", dueDate: codingDueDate)
	    // Display tasks
	    print("Task: \(gamingTask.taskName), Is overdue = \(gamingTask.isOverdue() ? "Yes" : "No")")
	    print("Task: \(codingTask.taskName), Is overdue =\(codingTask.isOverdue() ? "Yes" : "No")")
	    // Mark Coding task as completed
	    codingTask.markAsCompleted()
	    print("\nAfter marking Coding task as completed:")
	    print("Task: \(codingTask.taskName), Is completed = \(codingTask.isCompleted ? "Yes" : "No")")
	}
	


class BankAccount{
  var accountNumber:String
  var AccountHolderName:String
  var balance:Double
        init(accountNumber:String,AccountHolderName:String,balance:Double)
        {
          self.accountNumber = accountNumber
          self.AccountHolderName = AccountHolderName
          self.balance = balance
        } 
  
  func deposit(amount:Double)
  {
     balance+=amount
     print("balannce is\(balance) after adding amount = \(amount)")
  }
  func withdraw(amount:Double)
  {
    if amount > balance
    {
      print("insufficient funds ")
    }
    else {
      balance -= amount
      print("withsraw sucseefull balance is \(balance)")
    }
  }
  func displayBalance()
  {
    print("balance is \(balance)")
  }
  func transfer(amount:Double, to recipient:BankAccount){
            if amount > balance
            {
              print("insufficient funds")
            }
            else{
                 withdraw(amount:amount)
                 recipient.deposit(amount:amount)
                 print("transfered \(amount) to \(recipient.AccountHolderName)")
            }
  }
}
let account1 = BankAccount(accountNumber:"321" , AccountHolderName:"chaitanya", balance:00.00)
let account2 = BankAccount(accountNumber:"341" , AccountHolderName:"ajay", balance:00.00)
account1.deposit(amount:1000)
account1.withdraw(amount:200)
account1.displayBalance()
account1.transfer(amount:300,to:account2)
account1.displayBalance()


Your app has different user roles: admin, moderator, user, and guest.
	• Create an enum to represent the roles.
	• Define a function that takes a role as input and returns the permissions available for that role.
	
	Ans- >
	
	/*Your app has different user roles: admin, moderator, user, and guest.
	Create an enum to represent the roles.
	Define a function that takes a role as input and returns the permissions available for that role.*/
	
	
	enum UserRole {
	    case admin, moderator, user, guest
	}
	func getPermissions(for role: UserRole) -> String {
	    switch role {
	    case .admin:
	        return "complete authority: Manage users, edit , view "
	    case .moderator:
	        return " Edit , view reports"
	    case .user:
	        return " View , comment"
	    case .guest:
	        return "View-data"
	    }
	}
	let role = UserRole.admin
	print("this is for :\(role)")
	print(getPermissions(for: role))
	let roles = UserRole.moderator
	print("this is for :\(roles)")
	print(getPermissions(for:roles))
	let scroll = UserRole.user
	print("this is for :\(scroll)")
	print(getPermissions(for:scroll))
	


Your app supports multiple payment methods: creditCard, debitCard, paypal, and applePay.
	• Create an enum for payment methods, including associated values (e.g., card number or email for PayPal).
	• Write a function that processes the payment based on the selected method.

Design a delegation pattern using protocols where a WeatherService class fetches weather updates and notifies a delegate about success or failure. The delegate should implement a protocol WeatherServiceDelegate with methods didFetchWeather(data:) and didFailWithError(error:). Simulate the behavior by creating a mock delegate.

Ans - 


SwwiftUi

struct ContentView: View {
    @State private var isTransactionFormPresented = false

    var body: some View {
        NavigationView {
            VStack {
                Button(action: {
                    // Show the Transaction Form
                    isTransactionFormPresented.toggle()
                }) {
                    Text("Add Transaction")
                        .fontWeight(.bold)
                        .frame(maxWidth: .infinity)
                        .padding()
                        .background(Color.blue)
                        .foregroundColor(.white)
                        .cornerRadius(10)
                }
                .navigationTitle("Home")
                .navigationBarTitleDisplayMode(.inline)
                .sheet(isPresented: $isTransactionFormPresented) {
                    TransactionFormView()
                }
            }
        }
    }
}
 
// Transaction Form View
struct TransactionFormView: View {
    @State private var amount: String = ""
    @State private var category: String = "Income"
    @State private var description: String = ""

    @Environment(\.dismiss) var dismiss // This will help navigate back to the previous screen after saving

    let categories = ["Income", "Expense"]

    var body: some View {
        NavigationView {
            Form {
                Section(header: Text("Transaction Details")) {
                    TextField("Amount", text: $amount)
                        .keyboardType(.decimalPad)

                    TextField("Description", text: $description)

                    Picker("Category", selection: $category) {
                        ForEach(categories, id: \.self) { cat in
                            Text(cat)
                        }
                    }
                    .pickerStyle(SegmentedPickerStyle())
                }

                Button(action: {
                    // Action to save the transaction
                    saveTransaction()
                }) {
                    Text("Save Transaction")
                        .fontWeight(.bold)
                        .frame(maxWidth: .infinity)
                        .padding()
                        .background(Color.blue)
                        .foregroundColor(.white)
                        .cornerRadius(10)
                }
            }
            .navigationTitle("New Transaction")
        }
    }

    private func saveTransaction() {
        // Convert amount to a numeric value
        guard let transactionAmount = Double(amount) else {
            // Handle invalid input
            print("Invalid amount")
            return
        }

        let transaction = Transaction(amount: transactionAmount, category: category, description: description)
        // You can now save the transaction or pass it to a view model
        print("Saved Transaction: \(transaction)")

        // Dismiss the current view (navigate back)
        dismiss()
    }
}
 
struct Transaction {
    var amount: Double
    var category: String
    var description: String
}
 
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
 


 9/1/2025
1.intro kotlin
2.nullability
3.functions






Val - is used fro single time assignment
Var - id used for multiple assignment





Learn Kotlin From Zero to Hero in 10 Hours



10/1/2025
1.class and object
2.interface
3.init method
4.primary and secondary constructor
5.value class
6.inline class
7.enum class
8.inner class
9.object in kotlin
Here in  kolin in class we only have data and functions
	5. Late initilalize - 
---for inherting class we need to write open at starting of clas  so we caninherit that class



11. Write a program by creating an 'Employee' class having the following methods
and print the final salary.
1 - 'getInfo()' which takes the salary, number of hours of work per day of employee
as parameter
2 - 'AddSal()' which adds $10 to salary of the employee if it is less than $500.
3 - 'AddWork()' which adds $5 to salary of employee if the number of hours of
work per day is more than 6 hours.
 


te a program to print the area of a rectangle by creating a class named 'Area'
having two methods. First method named as 'setDim' takes length and breadth of
rectangle as parameters and the second method named as 'getArea' returns the area
of the rectangle. Length and breadth of rectangle are entered through keyboard.
2.
Create a class named 'Student' with String variable 'name' and integer variable
'roll_no'. Assign the value of roll_no as '2' and that of name as "John" by creating an
object of the class Student.
3.
Assign and print the roll number, phone number and address of two students having
names "Sam" and "John" respectively by creating two objects of class 'Student
'.
4.

1. Create class SimpleSpice. 
1. The class should have a String property for the name of the spice, and a String
for the level of spiciness.
2. Set the default name to curry and the spiciness to mild. 
3. Using a string for spiciness is nice for users, but not useful for calculations. Add
a heat property to your class with a getter that returns a numeric value for
spiciness. Use a value of 5.
4. Create an instance of SimpleSpice and print out its name, spiciness, and heat.
 
2. Let's improve the SimpleSpice class so that we can have various spices with different
levels of spiciness. 
1. Create a new class, Spice. 
2. Constructor should have a mandatory String argument for the name, and a
String argument for the level of spiciness where the default value is "mild" for
not spicy.
3. Add a variable, "heat", to your class, with a getter that returns a numeric value
for each type of spiciness (integer values ranging from 1 for "mild" to 10 for
"expremelly spicy")
4. Create a list of Spice objects and give each object a name and a spiciness level. 
5. Add to Spice an init block that prints out the values for the object after it has
been created.
6. Create a list of spices that are spicy or less than spicy. Hint: Use a filter and the
heat property.
7. Because salt is a very common spice, create a helper function called makeSalt().

11/1/2025

1.collections
2.arrays

Scenario: You are developing an employee management system where each employee has the following attributes:
	• Name
	• Age
	• Department
	• Salary
Questions:
	1. Define a data class for the employee with appropriate properties.
	2. Create a list of employees and implement the following: 
		○ Find the average salary of employees in the "Engineering" department.
		○ List all employees above the age of 30.
		○ Sort employees by salary in descending order.
	3. Update the salary of an employee when given the name. Ensure immutability using copy() (in languages like Kotlin).
	4. Add an optional field for address and handle cases where the address might be null.
	
	
	
	Scenario: You are tasked with implementing a shopping cart for an e-commerce app. Each item in the cart is represented as a data class.
	Questions:
	Define a data class for a shopping cart item with attributes:
		• Product name
		• Price
		• Quantity
	Write a function to calculate the total price of all items in the cart.
	If a discount is applicable on a specific product, create a method to update the price while maintaining immutability.
	Create a method to merge two carts and ensure no duplicate items exist (use product name as the key).


























































Kotlin Api,navigation,old java android concepts,json,Http
fireBase

13/1/2025
If we use suspend then it runs(function) on seprate thread and main thraed run independently
Kotlin Progerss bar
Toggle key



15/1/2025
Api
Retrofit







dataClass
Intrface
Retrofit



16/1/2025
1.navigation
17/12/2025
Binding
Viw binding
Data binding
18/1/2025

<LinearLayout
android:layout_width="match_parent"
android:layout_height="wrap_content"
android:orientation="vertical"
android:layout_margin="10dp"
android:gravity="center">
<!--TODO:Updateblankfragmentlayout-->
<TextView
android:layout_width="match_parent"
android:layout_height="match_parent"
android:text="@string/hello_blank_fragment"/>
<EditText
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:id="@+id/cityText"
android:hint="entercity"
android:textSize="28dp"/>
<Button
android:layout_width="wrap_content"
android:layout_height="match_parent"
android:layout_margin="10dp"
android:text="enter"
android:id="@+id/cityButton"/>

23/1/2025
Swift
Closure
2.optional
3.Protocol



com

2/1/2025









 iNSURANCEApi -  https://677636ef12a55a9a7d0ae13a.mockapi.io/company

Retrofit - https://square.github.io/retrofit/

Apis - https://github.com/public-apis/public-apis

31/12/2024
1.ActionBar



3/2/2024

https://console.cloud.google.com/google/maps-apis/home?project=maps-project-demo-369217
 

Project to make for practice  links-

1.Crud App FireBase -  Store, Retrieve, Search, Delete and Update Data using Firebase Realtime Database in Android Studio



2 - Shoe CartApplication
Shoe App ( Cart Management with Local DB) -  ( EXECUTORS , MVVM and ROOM )



3.To Do List App Introduction ( Using Sqlite DataBase 2020 )



Component practice reamin
1.constraint layout
2.recycler view
2.list view
3.onbindView
4.Adapter

Chaitanya  mahesh gondkar  - (Android Development)
1.coffeShop project on android studio in this  we did
Fragment tutorial 

27/12/2024
     
	1. Make to do app
	2. Learn layouts … 
	3. View in android
	4. Learn ui
	5. Intent,fragment,bundle
	6. Learn types of  layouts in android
	7. lists

Roadmap to learn Android App Development
	• Programming
		○ Java
		○ Kotlin
		○ 
	• 3rd Party Library
		○ Image Loading
			§ Glide
			§ Picasso
		○ Dependency Injection
			§ Dagger
		○ Networking
			§ Fast Android Networking Library
			§ Retrofit
		○ MultiThreading
			§ RxJava
			§ Coroutines
			§ Kotlin Flow API
	• Coroutines - You can learn these topics here: Master Kotlin Coroutines
		○ coroutines
		○ suspend
		○ launch, async-await, withContext
		○ dispatchers
		○ scope, context, job
		○ lifecycleScope, viewModelScope, GlobalScope
		○ suspendCoroutine, suspendCancellableCoroutine
		○ coroutineScope, supervisorScope
	• Kotlin Flow API - You can learn these topics here: Kotlin Flow API
		○ Flow Builder, Operator, Collector
		○ flowOn, dispatchers
		○ Operators such as filter, map, zip, flatMapConcat, retry, debounce, distinctUntilChanged, flatMapLatest
		○ Terminal operators
		○ Cold Flow vs Hot Flow: Cold Flow vs Hot Flow
		○ StateFlow, SharedFlow, callbackFlow, channelFlow
	• Data Format
		○ JSON
			§ GSON
		○ Flat Buffer
		○ Protocol Buffer
	• Networking
		○ GET/POST/DELETE/PUT/PATCH
		○ OkHttp, Interceptor
		○ Caching
		○ Retrofit with Coroutines/Flow
		○ Multipart request
		○ Read, Write Timeout
		○ OAuth 2.0 - Refresh and Access Token
		○ HTTP Status Codes
	• Android Jetpack
		○ Foundation Components
			§ AppCompat
			§ Android KTX
			§ Multidex
		○ Architecture Components
			§ LiveData
			§ ViewModel
			§ DataBinding
			§ Paging
			§ Work Manager
			§ Navigation
		○ Behaviour Components
			§ Download Manager
			§ Media Playback
			§ Notification
			§ Permissions
			§ Preference
			§ Sharing
			§ Slice
		○ UI Component
			§ Animation & Transition
			§ Android Auto
			§ Emoji
			§ Palette
			§ Android TV
			§ Android Wear
	• Compose
		○ State: remember, rememberSaveable, MutableState
		○ Recomposition
		○ State hoisting
		○ Side-effects
		○ Modifier
		○ Theme
		○ Layout, List
		○ Gestures, Animation
		○ CompositionLocal
	• Common Design Patterns and Architecture
		○ Builder Pattern
		○ Singleton
		○ Dependency Injection
		○ Factory
		○ Observer
		○ Repository
		○ MVVM
		○ MVP
		○ MVI
		○ Clean architecture
	• Unit Testing
		○ Local Unit Testing
		○ Instrumentation Testing
	• Firebase
		○ FCM
		○ Crashlytics
		○ Analytics
		○ Remote Config
		○ App Indexing
		○ Dynamic Link
	• Security
		○ Encrypt / Decrypt
		○ Proguard
		○ R8
	• App Release
		○ .keystore file
		○ App Bundle
		○ Playstore
	• Keep Learning
	• Android Studio
		○ Android Studio IDE Overview
		○ Project Structure
			§ Java/Kotlin
			§ XML
			§ .gradle files
	• Android Component
		○ Activity
			§ Activity Lifecycle
			§ Tasks & Back Stack
		○ Service
		○ Broadcast Receiver
		○ Content Provider
	• Intents
		○ Types of Intent
			§ Implicit
			§ Explicit
		○ Intent Filter
	• Static User Interface
		○ View
			§ Button, ImageView, TextView, EditText etc
		○ ViewGroup
			§ LinearLayout, RelativeLayout, FrameLayout, ConstraintLayout
	• Dynamic User Interface
		○ RecyclerView
		○ ViewPager
		○ Spinner
	• CustomView
		○ Canvas
		○ Bitmap
		○ Paint
	• UI Resources
		○ Drawables
		○ String
		○ Styles
	• Fragments
		○ Fragment Lifecycle
		○ Fragment Manager
	• Support User Interface
		○ ProgressBar
		○ Dialogs
		○ Toast & Snackbar
	• Storage
		○ Shared Preferences
		○ DataStore
		○ File Systems
		○ Database
			§ RoomDB
	• Build
		○ Gradle
		○ Debug / Release Configuration
	• Threading
		○ Thread
		○ Handler/Looper
		○ ThreadPoolExecutor
		○ RxJava
		○ Coroutines/Flow
		○ WorkManager
	• Debugging
		○ Memory profiling
		○ Logging
		○ Systrace
		○ Exceptions
		○ Error Handling
	• Memory Leak
		○ Detecting and Fixing Memory Leaks
		○ Context and Improving

28/12/2024  - class notes

1.MAM made todo list with sql lite database          

 RoomDB to App - 
 1. Add the dependency, app's build.gradle,
 under dependencies section implementation("androidx.room:room-runtime:2.6.1") annotationProcessor("androidx.room:room-compiler:2.6.1") 
2. Annotate your bean/model with @Entity, @PrimaryKey (autoGenerate=true) 
3. DAO interface- with @Insert, @Query, @Update, @Delete
 4. AppDatabase

5e9ad8ca216649e1996b388dd5ee97d0

From <https://newsapi.org/register/success> 

https://newsapi.org/v2/everything?q=keyword&apiKey=5e9ad8ca216649e1996b388dd5ee97d0

54d19b247ee4f36e82a8b0ff3a961ef9 -open weather api key

pub_65800517779116987d6ff4fcef26c33cf1ca9 - newa PI KEY


Travel_Api

https://api.aviationstack.com/v1/flights?access_key=3de2f0ad8bd326e1426234de8fd8705c

https://jsonplaceholder.typicode.com/users  - user api

https://jsonplaceholder.typicode.com/users -free use link

//packagecom.example.mymovieapp_two.Model.Ui
//
//importandroid.os.Bundle
//importandroidx.fragment.app.Fragment
//importandroid.view.LayoutInflater
//importandroid.view.View
//importandroid.view.ViewGroup
//importandroidx.navigation.fragment.findNavController
//importandroidx.recyclerview.widget.LinearLayoutManager
//importandroidx.recyclerview.widget.RecyclerView
//importcom.example.mymovieapp_two.Model.Adapter.MovieAdapter
//importcom.example.mymovieapp_two.Model.Model.Movie
//importcom.example.mymovieapp_two.Model.Service.MovieApi
//importcom.example.mymovieapp_two.R
//importretrofit2.Call
//importretrofit2.Callback
//importretrofit2.Response
//
//
//classMovieListFragment:Fragment(){
//privatelateinitvarrecyclerView:RecyclerView
//privatevarmovieapi=MovieApi.create()
//
//overridefunonCreateView(
//inflater:LayoutInflater,container:ViewGroup?,
//savedInstanceState:Bundle?
//):View?{
//valview=inflater.inflate(R.layout.fragment_movie_list,container,false)
//
//recyclerView=view.findViewById(R.id.recyclerview)
//recyclerView.layoutManager=LinearLayoutManager(requireContext())
//fetchMovies()
//returnview
//}
//
//privatefunfetchMovies(){
//
//movieapi.GetallData("tt3896198","f66c290e").enqueue(object:Callback<Movie>{
//overridefunonResponse(call:Call<Movie>
//,response:Response<Movie>){
//if(response.isSuccessful)
//{
//valMovies=response.body()?.imdbID?.isEmpty()
//recyclerView.adapter=MovieAdapter(Movies){selectedMovie->
//valaction=MovieListFragmentDirections.actionMovieListFragmentToMovieDetailFragment(selectedMovie)
//findNavController().navigate(action)
//}
//}
//}
//
//overridefunonFailure(call:Call<Movie>,t:Throwable){
//}
//
//})
//
//
//
//
//
//}
//

View model
Dagger
hilt

packagecom.example.mileston_assesment2_chaitanyagondkar.UI

importandroid.os.Bundle
importandroidx.fragment.app.Fragment
importandroid.view.LayoutInflater
importandroid.view.View
importandroid.view.ViewGroup
importandroid.widget.Button
importandroid.widget.TextView
importandroid.widget.Toast
importandroidx.navigation.fragment.findNavController
importcom.example.mileston_assesment2_chaitanyagondkar.Model.WeatherModel
importcom.example.mileston_assesment2_chaitanyagondkar.R
importcom.example.mileston_assesment2_chaitanyagondkar.Serevice.RetrFitInstance
importretrofit2.Call
importretrofit2.Callback
importretrofit2.Response


classMainFragment:Fragment(){


overridefunonCreateView(
inflater:LayoutInflater,container:ViewGroup?,
savedInstanceState:Bundle?
):View?{
//Inflatethelayoutforthisfragment
valview=inflater.inflate(R.layout.fragment_main,container,false)
valtexts=view.findViewById<TextView>(R.id.texttt)
valButton=view.findViewById<Button>(R.id.button)
Button.setOnClickListener(fetchdata())
returnview
}

privatefunfetchdata(){
TODO("Notyetimplemented")
RetrFitInstance.api.getalldata("2fd5425d8ce909772fc8120bb45f3b01","city").enqueue(object:Callback<WeatherModel>{

overridefunonResponse(
call:Call<WeatherModel>,
response:Response<WeatherModel>
){
if(response.isSuccessful){
valdetails=response.body()
MainFragmentDirections.actionMainFragmentToDetailFragment(details)
findNavController().navigate(details)
}
else
{

Toast.makeText(requireContext()."failedtofetrch",Toast.LENGTH_SHORT).Show()


}

overridefunonFailure(call:Call<WeatherModel>,t:Throwable){


Toast.makeText(requireContext(),"${t.message}",Toast.LENGTH_SHORT).show()
}

}
})










}

}


import java.util.List;
import java.util.ArrayList;

public class Main
{
	public static void main(String[] args) {
	    
	    List<Integer> list = new ArrayList<>();
	    list.add(10);
	    list.add(20);
	    list.add(30);
	    list.add(40);
	    list.add(50);
	    System.out.println(list);
	    	    List<Integer> nlist = new ArrayList<>();
        nlist.add(56);
	    nlist.add(70);
	    nlist.add(80);
	    System.out.println(nlist);
	    nlist.addAll(list);
	    	    System.out.println(nlist);
	    	    	    	    System.out.println(nlist.get(1));
           nlist.remove(1);
	    	    System.out.println(nlist);
	    	    nlist.remove(Integer.valueOf(80));
	    	    	    	    System.out.println(nlist);
	    	    	    	            //   nlist.clear();
	    	    	    	            //   	    	    System.out.println(nlist);
	    	    	    	            nlist.set(1,45);
	    	    	    	            	    	    	    	    System.out.println(nlist);


	    	    	    	               






	    
	}
}

22-1-2025




// var chaitanya = "cmg"
// print(chaitanya)
// var chaotanya:String = "cmghdhd"
// print(chaotanya)
// var dobby = 120.2
// var a = chaitanya + String(dobby)
// print(a)
// print("value of double is = \(dobby) ")
// print("let equation 6*9 is \(6*9) is not 42!")
// let myarr = ["chaitanya","shradha","ketaki","yasheee",]
// let secondelement = myarr[3]
// print(secondelement)
// var mutablelist = myarr
// mutablelist[2]="pillya"
// print(mutablelist)
// let emptyarray = Array<String>()
// var someoptional:String? = "haromine"
// var sumnum = 4
// if let num =sumnum , num>1
// {
//   print("you can do it chaiyanya")
// }
let someNumber: Int? = 7
if let num = someNumber, num > 3 {
    print("num is not nil and is greater than 3")
}
let hunter:Int?=5
if let num = hunter,num>2
{
  print("chaitanya you can do it")
}

28/1/2025




Bank Account and Savings Account Classes
You are building a banking application. The BankAccount class has basic account details like balance and a method deposit(). The SavingsAccount class inherits from BankAccount and adds a property interestRate and a method to calculate interest.
	• How would you implement inheritance in this scenario?
	• Create a function in the SavingsAccount class to calculate and display the interest based on the current balance.

Ans - >

Closure- 26/1/2025 swift practice

// var greetings="hello iam chaitanya gondkar"
// greetings = " "
//  print(greetings)
//  var closure : (() -> Void)
//  func getData(param:Int)
// {
 // }

// func ParameterFunc(param:(() -> String))
// {
//       print(param())
// }
// ParameterFunc{
//   return "heyy gys"
// }

// func shows(name:(()-> String)){  print(name())}
// shows{
//   return "chaitnay "
// }

func showData(param:((String) -> String))
{       let c = "chaitanya"
       print(param(c))
}
showData { Stringval in 
  return Stringval + "hello ji"

}




func shows(param:((String)->String))
{
  let Hi = "Chaitanya"
   print(param(Hi))
}
shows{sub in
  return sub +  "you can do any thing jo bhi chahu wo mein pau jindaggi mein jit jau ba sitnsa khha b hain"
}







Employee and Manager Class
You are building an employee management system. You have an Employee class that holds basic employee details such as name, id, and salary. You also need to create a Manager class that inherits from Employee, with additional properties like department and teamSize.
	• How would you design these classes using inheritance in Swift?
	• Implement a function in the Manager class to print the details of the manager, including the department and team size.
	•  
	// Base class
	class Employee {
	    var name: String
	    var id: Int
	    var salary: Double
	
	    init(name: String, id: Int, salary: Double) {
	        self.name = name
	        self.id = id
	        self.salary = salary
	    }
	
	    func displayDetails() {
	        print("Employee Name: \(name), ID: \(id), Salary: \(salary)")
	    }
	}
	
	// Subclass
	class Manager: Employee {
	    var department: String
	    var teamSize: Int
	
	    init(name: String, id: Int, salary: Double, department: String, teamSize: Int) {
	        self.department = department
	        self.teamSize = teamSize
	        super.init(name: name, id: id, salary: salary)
	    }
	
	    func displayManagerDetails() {
	        super.displayDetails() // Call the base class method
	        print("Department: \(department), Team Size: \(teamSize)")
	    }
	}
	
	// Example usage
	let manager = Manager(name: "John Doe", id: 101, salary: 75000, department: "Engineering", teamSize: 8)
	manager.displayManagerDetails()
	

Optionals-



Swift

class BankAccount {
    var accountNumber: String
    var accountHolderName: String
    var balance: Double
    
    init(accountNumber: String, accountHolderName: String, initialBalance: Double) {
        self.accountNumber = accountNumber
        self.accountHolderName = accountHolderName
        self.balance = initialBalance
    }
    
    func deposit(amount: Double) {
        balance += amount
        print("Deposited \(amount). New balance: \(balance)")
    }
    
    func withdraw(amount: Double) {
        if amount > balance {
            print("Insufficient funds. Current balance: \(balance)")
        } else {
            balance -= amount
            print("Withdrew \(amount). New balance: \(balance)")
        }
    }
    
    func displayBalance() {
        print("Account Number: \(accountNumber) | Account Holder: \(accountHolderName) | Balance: \(balance)")
    }
    
    func transfer(amount: Double, to recipient: BankAccount) {
        if amount > balance {
            print("Transfer failed. Insufficient balance.")
        } else {
            withdraw(amount: amount)
            recipient.deposit(amount: amount)
            print("Transferred \(amount) from \(accountNumber) to \(recipient.accountNumber).")
        }
    }
}
// Example usage:
let account1 = BankAccount(accountNumber: "7864", accountHolderName: "chaitanya", initialBalance: 1000)
let account2 = BankAccount(accountNumber: "8567", accountHolderName: "wipro", initialBalance: 500)
account1.deposit(amount: 200)
account1.withdraw(amount: 300)
account1.displayBalance()
account1.transfer(amount: 400, to: account2)
account1.displayBalance()


Question:Implement a ShoppingCart class in Swift. It should: Contain an array of Product objects. Allow adding and removing products from the cart. Calculate the total cost of the items in the cart.
Ans. - >

// Product class
class Product {
    let name: String
    let price: Double
    
    init(name: String, price: Double) {
        self.name = name
        self.price = price
    }
}
// ShoppingCart class
class ShoppingCart {
    private var products: [Product] = []
        func addProduct(_ product: Product) {
        products.append(product)
    }
    func removeProduct(_ product: Product) {
        products.removeAll { $0.name == product.name }
    }
    
    // Calculate total cost
    func calculateTotalCost() -> Double {
        return products.reduce(0) { $0 + $1.price }
    }
    
    // Display cart contents
    func displayCart() {
        print("Cart Contents:")
        for product in products {
            print("-prodcut name rs  = \(product.name): and price is rs\(product.price)")
        }
        print("Total amoubnt: rs\(calculateTotalCost())")
    }
}
// Example usage
let apple = Product(name: "bokok", price: 100)
let banana = Product(name: "plates", price: 545)
let cart = ShoppingCart()
cart.addProduct(apple)
cart.addProduct(banana)
cart.displayCart()
cart.removeProduct(banana)
cart.displayCart()


Q.

Question:Create a Task class to manage tasks in a task management system. Each task should have:
	• A taskName and dueDate.
	• A method to mark the task as completed.
	• A method to check if the task is overdue (i.e., if the dueDate has passed)
	• Ans - >
     



Bank Account and Savings Account Classes
You are building a banking application. The BankAccount class has basic account details like balance and a method deposit(). The SavingsAccount class inherits from BankAccount and adds a property interestRate and a method to calculate interest.
	• How would you implement inheritance in this scenario?
	• Create a function in the SavingsAccount class to calculate and display the interest based on the current balance.
	
	import Foundation
	class Task {
	    var taskName: String
	    var dueDate: Date
	    var isCompleted: Bool = false
	    init(taskName: String, dueDate: Date) {
	        self.taskName = taskName
	        self.dueDate = dueDate
	    }
	    func markAsCompleted() {
	        isCompleted = true
	    }
	    func isOverdue() -> Bool {
	        return Date() > dueDate && !isCompleted
	    }
	}
	// Example usage
	let formatter = DateFormatter()
	formatter.dateFormat = "yyyy-MM-dd"
	// Create tasks
	if let gamingDueDate = formatter.date(from: "2025-01-25"),
	   let codingDueDate = formatter.date(from: "2025-01-20") {
	    let gamingTask = Task(taskName: "Gaming", dueDate: gamingDueDate)
	    let codingTask = Task(taskName: "Coding", dueDate: codingDueDate)
	    // Display tasks
	    print("Task: \(gamingTask.taskName), Is overdue = \(gamingTask.isOverdue() ? "Yes" : "No")")
	    print("Task: \(codingTask.taskName), Is overdue =\(codingTask.isOverdue() ? "Yes" : "No")")
	    // Mark Coding task as completed
	    codingTask.markAsCompleted()
	    print("\nAfter marking Coding task as completed:")
	    print("Task: \(codingTask.taskName), Is completed = \(codingTask.isCompleted ? "Yes" : "No")")
	}
	


class BankAccount{
  var accountNumber:String
  var AccountHolderName:String
  var balance:Double
        init(accountNumber:String,AccountHolderName:String,balance:Double)
        {
          self.accountNumber = accountNumber
          self.AccountHolderName = AccountHolderName
          self.balance = balance
        } 
  
  func deposit(amount:Double)
  {
     balance+=amount
     print("balannce is\(balance) after adding amount = \(amount)")
  }
  func withdraw(amount:Double)
  {
    if amount > balance
    {
      print("insufficient funds ")
    }
    else {
      balance -= amount
      print("withsraw sucseefull balance is \(balance)")
    }
  }
  func displayBalance()
  {
    print("balance is \(balance)")
  }
  func transfer(amount:Double, to recipient:BankAccount){
            if amount > balance
            {
              print("insufficient funds")
            }
            else{
                 withdraw(amount:amount)
                 recipient.deposit(amount:amount)
                 print("transfered \(amount) to \(recipient.AccountHolderName)")
            }
  }
}
let account1 = BankAccount(accountNumber:"321" , AccountHolderName:"chaitanya", balance:00.00)
let account2 = BankAccount(accountNumber:"341" , AccountHolderName:"ajay", balance:00.00)
account1.deposit(amount:1000)
account1.withdraw(amount:200)
account1.displayBalance()
account1.transfer(amount:300,to:account2)
account1.displayBalance()


Your app has different user roles: admin, moderator, user, and guest.
	• Create an enum to represent the roles.
	• Define a function that takes a role as input and returns the permissions available for that role.
	
	Ans- >
	
	/*Your app has different user roles: admin, moderator, user, and guest.
	Create an enum to represent the roles.
	Define a function that takes a role as input and returns the permissions available for that role.*/
	
	
	enum UserRole {
	    case admin, moderator, user, guest
	}
	func getPermissions(for role: UserRole) -> String {
	    switch role {
	    case .admin:
	        return "complete authority: Manage users, edit , view "
	    case .moderator:
	        return " Edit , view reports"
	    case .user:
	        return " View , comment"
	    case .guest:
	        return "View-data"
	    }
	}
	let role = UserRole.admin
	print("this is for :\(role)")
	print(getPermissions(for: role))
	let roles = UserRole.moderator
	print("this is for :\(roles)")
	print(getPermissions(for:roles))
	let scroll = UserRole.user
	print("this is for :\(scroll)")
	print(getPermissions(for:scroll))
	


Your app supports multiple payment methods: creditCard, debitCard, paypal, and applePay.
	• Create an enum for payment methods, including associated values (e.g., card number or email for PayPal).
	• Write a function that processes the payment based on the selected method.

Design a delegation pattern using protocols where a WeatherService class fetches weather updates and notifies a delegate about success or failure. The delegate should implement a protocol WeatherServiceDelegate with methods didFetchWeather(data:) and didFailWithError(error:). Simulate the behavior by creating a mock delegate.

Ans - 


SwwiftUi

struct ContentView: View {
    @State private var isTransactionFormPresented = false

    var body: some View {
        NavigationView {
            VStack {
                Button(action: {
                    // Show the Transaction Form
                    isTransactionFormPresented.toggle()
                }) {
                    Text("Add Transaction")
                        .fontWeight(.bold)
                        .frame(maxWidth: .infinity)
                        .padding()
                        .background(Color.blue)
                        .foregroundColor(.white)
                        .cornerRadius(10)
                }
                .navigationTitle("Home")
                .navigationBarTitleDisplayMode(.inline)
                .sheet(isPresented: $isTransactionFormPresented) {
                    TransactionFormView()
                }
            }
        }
    }
}
 
// Transaction Form View
struct TransactionFormView: View {
    @State private var amount: String = ""
    @State private var category: String = "Income"
    @State private var description: String = ""

    @Environment(\.dismiss) var dismiss // This will help navigate back to the previous screen after saving

    let categories = ["Income", "Expense"]

    var body: some View {
        NavigationView {
            Form {
                Section(header: Text("Transaction Details")) {
                    TextField("Amount", text: $amount)
                        .keyboardType(.decimalPad)

                    TextField("Description", text: $description)

                    Picker("Category", selection: $category) {
                        ForEach(categories, id: \.self) { cat in
                            Text(cat)
                        }
                    }
                    .pickerStyle(SegmentedPickerStyle())
                }

                Button(action: {
                    // Action to save the transaction
                    saveTransaction()
                }) {
                    Text("Save Transaction")
                        .fontWeight(.bold)
                        .frame(maxWidth: .infinity)
                        .padding()
                        .background(Color.blue)
                        .foregroundColor(.white)
                        .cornerRadius(10)
                }
            }
            .navigationTitle("New Transaction")
        }
    }

    private func saveTransaction() {
        // Convert amount to a numeric value
        guard let transactionAmount = Double(amount) else {
            // Handle invalid input
            print("Invalid amount")
            return
        }

        let transaction = Transaction(amount: transactionAmount, category: category, description: description)
        // You can now save the transaction or pass it to a view model
        print("Saved Transaction: \(transaction)")

        // Dismiss the current view (navigate back)
        dismiss()
    }
}
 
struct Transaction {
    var amount: Double
    var category: String
    var description: String
}
 
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
 


 9/1/2025
1.intro kotlin
2.nullability
3.functions






Val - is used fro single time assignment
Var - id used for multiple assignment





Learn Kotlin From Zero to Hero in 10 Hours



10/1/2025
1.class and object
2.interface
3.init method
4.primary and secondary constructor
5.value class
6.inline class
7.enum class
8.inner class
9.object in kotlin
Here in  kolin in class we only have data and functions
	5. Late initilalize - 
---for inherting class we need to write open at starting of clas  so we caninherit that class



11. Write a program by creating an 'Employee' class having the following methods
and print the final salary.
1 - 'getInfo()' which takes the salary, number of hours of work per day of employee
as parameter
2 - 'AddSal()' which adds $10 to salary of the employee if it is less than $500.
3 - 'AddWork()' which adds $5 to salary of employee if the number of hours of
work per day is more than 6 hours.
 


te a program to print the area of a rectangle by creating a class named 'Area'
having two methods. First method named as 'setDim' takes length and breadth of
rectangle as parameters and the second method named as 'getArea' returns the area
of the rectangle. Length and breadth of rectangle are entered through keyboard.
2.
Create a class named 'Student' with String variable 'name' and integer variable
'roll_no'. Assign the value of roll_no as '2' and that of name as "John" by creating an
object of the class Student.
3.
Assign and print the roll number, phone number and address of two students having
names "Sam" and "John" respectively by creating two objects of class 'Student
'.
4.

1. Create class SimpleSpice. 
1. The class should have a String property for the name of the spice, and a String
for the level of spiciness.
2. Set the default name to curry and the spiciness to mild. 
3. Using a string for spiciness is nice for users, but not useful for calculations. Add
a heat property to your class with a getter that returns a numeric value for
spiciness. Use a value of 5.
4. Create an instance of SimpleSpice and print out its name, spiciness, and heat.
 
2. Let's improve the SimpleSpice class so that we can have various spices with different
levels of spiciness. 
1. Create a new class, Spice. 
2. Constructor should have a mandatory String argument for the name, and a
String argument for the level of spiciness where the default value is "mild" for
not spicy.
3. Add a variable, "heat", to your class, with a getter that returns a numeric value
for each type of spiciness (integer values ranging from 1 for "mild" to 10 for
"expremelly spicy")
4. Create a list of Spice objects and give each object a name and a spiciness level. 
5. Add to Spice an init block that prints out the values for the object after it has
been created.
6. Create a list of spices that are spicy or less than spicy. Hint: Use a filter and the
heat property.
7. Because salt is a very common spice, create a helper function called makeSalt().

11/1/2025

1.collections
2.arrays

Scenario: You are developing an employee management system where each employee has the following attributes:
	• Name
	• Age
	• Department
	• Salary
Questions:
	1. Define a data class for the employee with appropriate properties.
	2. Create a list of employees and implement the following: 
		○ Find the average salary of employees in the "Engineering" department.
		○ List all employees above the age of 30.
		○ Sort employees by salary in descending order.
	3. Update the salary of an employee when given the name. Ensure immutability using copy() (in languages like Kotlin).
	4. Add an optional field for address and handle cases where the address might be null.
	
	
	
	Scenario: You are tasked with implementing a shopping cart for an e-commerce app. Each item in the cart is represented as a data class.
	Questions:
	Define a data class for a shopping cart item with attributes:
		• Product name
		• Price
		• Quantity
	Write a function to calculate the total price of all items in the cart.
	If a discount is applicable on a specific product, create a method to update the price while maintaining immutability.
	Create a method to merge two carts and ensure no duplicate items exist (use product name as the key).


























































Kotlin Api,navigation,old java android concepts,json,Http
fireBase

13/1/2025
If we use suspend then it runs(function) on seprate thread and main thraed run independently
Kotlin Progerss bar
Toggle key



15/1/2025
Api
Retrofit







dataClass
Intrface
Retrofit



16/1/2025
1.navigation
17/12/2025
Binding
Viw binding
Data binding
18/1/2025

<LinearLayout
android:layout_width="match_parent"
android:layout_height="wrap_content"
android:orientation="vertical"
android:layout_margin="10dp"
android:gravity="center">
<!--TODO:Updateblankfragmentlayout-->
<TextView
android:layout_width="match_parent"
android:layout_height="match_parent"
android:text="@string/hello_blank_fragment"/>
<EditText
android:layout_width="wrap_content"
android:layout_height="wrap_content"
android:id="@+id/cityText"
android:hint="entercity"
android:textSize="28dp"/>
<Button
android:layout_width="wrap_content"
android:layout_height="match_parent"
android:layout_margin="10dp"
android:text="enter"
android:id="@+id/cityButton"/>

23/1/2025
Swift
Closure
2.optional
3.Protocol



com

2/1/2025









 iNSURANCEApi -  https://677636ef12a55a9a7d0ae13a.mockapi.io/company

Retrofit - https://square.github.io/retrofit/

Apis - https://github.com/public-apis/public-apis

31/12/2024
1.ActionBar



3/2/2024

https://console.cloud.google.com/google/maps-apis/home?project=maps-project-demo-369217
 

![image](https://github.com/user-attachments/assets/3d995ac0-c864-4b84-b7a8-3ca814d95f58)
![image](https://github.com/user-attachments/assets/c5430093-b506-4aae-8b40-59ea540684d1)
