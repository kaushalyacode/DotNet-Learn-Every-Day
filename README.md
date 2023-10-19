<h1 align="center">Learn .NET Framwork</h1>

## Day one : Lean Records | Classes | Structs  and Deploy First Application Into Azure App Service

## 1.1 Records
### Learning Material : [Learn It here](https://code-maze.com/csharp-records/)

#### - records use value-based equality(number of properties and names of properties need to be same), whilst classes use memory-based equality(two objects are of the same class type, variables refer to the same object).

### Syntax
```c#
 public record Person
 {
     public string FirstName { get; set; }
     public string LastName { get; set; }
 }
```

```c#
public  record class Animal
{
    public string breed { get; set; }
}
```
```C#
public record Employee
{
    public Employee(string EmployeeID, string EmployeeNameX)
    {
        EmployeeID = EmployeeID;
        EmployeeNameX = EmployeeNameX;
    }
    public string EmployeeID { get; set; }
    public string EmployeeNameX { get; set; }
}
```
