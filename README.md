fun main(){
    val str:String
    str = "Welcome"
    print("Enter Name: ")
    val name:String = readLine()!!.toString()
    print("Enter Age: ")
    val age:Int = readLine()!!.toInt()
    print("Enter GPA: ")
    val GPA:Double = readLine()!!.toDouble()

    println("===== User Info =====")
    println("Name: $name")
    println("Age: $age")
    println("GPA: $GPA")

    var count =1
    println("Count: $count")
    count = 10
    println("Count: $count")

    var department:String?
    department = null
    department = "Software Engineering"
    print("Department: ${department!!}")


}
