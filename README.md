# java_inheritance
public class Main{
    public static void main(String args[])
    {
        FullTimeEmployee a = new FullTimeEmployee();
        a.name = "Lisa";
        a.employeeId = 101;
        a.salary = 50000;
        a.bonus = 10000;
        PartTimeEmployee b = new PartTimeEmployee();
        b.name="Riya";
        b.employeeId = 102;
        b.hoursWorked=40;
        b.hourlyRate=600;
        System.out.println("Full Time Employee Details");
        a.displayDetails();
        System.out.println("Part Time Employee Details");
        b.displayDetails();
    }
}
