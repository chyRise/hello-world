# hello-world
this is a test project 
class MyWorld{
  
  private String name; //名称
  private String international;//国籍
  private String dream; //梦想
  
  //空参构造
  public MyWorld(){
  }
  
  public MyWorld(String name,String international,String dream){
    this.name = name;
    this.international = international;
    this.dream = dream;
  }
  private String out(){
    return name+" "+international+" "+dream;
  }
}
