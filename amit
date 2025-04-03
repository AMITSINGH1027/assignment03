class Employee {
    private String name;
    private String jobTitle;
    private double salary;

    // Constructor
    public Employee(String name, String jobTitle, double salary) {
        this.name = name;
        this.jobTitle = jobTitle;
        this.salary = salary;
    }

    // Getter and Setter methods for name, jobTitle, and salary
    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getJobTitle() {
        return jobTitle;
    }

    public void setJobTitle(String jobTitle) {
        this.jobTitle = jobTitle;
    }

    public double getSalary() {
        return salary;
    }

    public void setSalary(double salary) {
        this.salary = salary;
    }

    // Method to get employee details
    public void displayEmployeeDetails() {
        System.out.println("Employee Name: " + name);
        System.out.println("Job Title: " + jobTitle);
        System.out.println("Salary: " + salary);
    }

    // Method to calculate salary increase
    public double calculateSalaryIncrease(double percentage) {
        return salary * (percentage / 100);
    }

    // Method to update salary
    public void updateSalary(double percentage) {
        if (percentage < 0) {
            System.out.println("Percentage increase cannot be negative.");
            return;
        }
        double increase = calculateSalaryIncrease(percentage);
        salary += increase;
        System.out.println("Updated Salary: " + salary);
    }

    public static void main(String[] args) {
        Employee emp = new Employee("Amit Singh", "Web Developer", 70000);
        emp.displayEmployeeDetails();
        
        System.out.println("Increasing salary by 10%...");
        emp.updateSalary(10);
    }
}
