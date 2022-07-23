# B-38-d6


class movie{
  constructor(title,studio,rating)
  {
    this.title=title;
    this.studio=studio;
    this.rating=rating;
    
  }
  getPG()
  {
    return"The "+this.title+"Is a movie of"+this.studio+"with"+this.rating;
  }
    
  }
  var mv1=new movie("Casino Royale ","Eon Productions ","PG­13");
  console.log(mv1.getPG());
  
  
  
  
  AREA AND CIRCUMFERENCE OF A CIRCLE
  ```````````````````````````````````
  
  class circle{
  constructor(radius,color)
  {
    this.radius=radius;
    this.color=color;
    
  }
  getarea()
  {
    return 3.14159265*this.radius*this.radius;
    
  }
  getcircumference()
  {
    return 2*this.radius*3.14159265;
}
}
  var mv1=new circle("1.0","red");
  console.log(mv1.getarea());
    console.log(mv1.getcircumference());
	
	
	
	CALCULATE UBER PRICE
	`````````````````````
	
	class ubercost{
  constructor(km,cpkm)
  {
    this.km=km;
    this.cpkm=cpkm;
    
  }
  getcost()
  {
    return this.km*this.cpkm;
    
  }
 
}
  var mv1=new ubercost("10","24");
 
    console.log(mv1.getcost());
	
	
	CLASS FUNCTION TO HOLD HIS DETAIL
	`````````````````````````````````
	
	class person{
  constructor(name,age,height,weight)
  {
    this.name=name;
    this.age=age;
    this.height=height;
    this.weight=weigth;
    
  }
  getdetail()
  {
    return "name"+this.name+"age"+ this.age+"height"+ this.height+"weight"+  this.weight;
    
  }
 
}
  var mv1=new person("seyoon","2","86","12");
 
    console.log(mv1.getdetail());
