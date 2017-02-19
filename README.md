#codePower
// A program to register a student with as many as seven modules. 
public class Module
{
  private String moduleCode;
  private String moduleName;
  
  Module()
  {
    moduleCode = "";
    moduleName = "";
  }
  
  Module(String mCode, String mName)
  {
    moduleCode = mCode;
    moduleName = mName;
  }
  
  public String getModuleCode()
  {
    return moduleCode;
  }
  
  public String getModuleName()
  {
    return moduleName;
  }
  
  public String toString()
  {
    return moduleName + "( " + moduleCode ")";
  }
}
