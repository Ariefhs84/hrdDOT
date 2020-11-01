# hrdDOT
Implementasi Class Diagram
<?php  

  Public class Company  { 
    
   public string name;
   
  } 
  
   public function getCompanyName() { return $this->name; } 
   
   public function setCompanyName($name) { $this->name = $name; } 
   
   
  Public class Department  { 
    
   public string name;
   
  }
  
   public function getDepartmentName() { return $this->name; } 
   
   public function setDepartmentName($name) { $this->name = $name; } 
   
   
   Public class Employee  { 
    
   public string name;
   
   public string title;
   
   public integer salary;
   
  }
  
  public function setEmployeetName($name) { $this->name = $name; } 
   
  
  public function getEmployeeName() { return $this->name; } 
   
   
    public function getEmployeeProfile() { return $this->name; } 
	
	 public function getEmployeeMonthlySalary($day) { return $this->day; } 
   
   
   
   
   
   
   
