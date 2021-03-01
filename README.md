# Petjava
public class Pet {

	private String name;
	private int age;
	private String location;
	private String type;
	
	
public Pet(String petName)
	{	
		name = petName;
		age = 0;
		location = "";
		type = "";
	}
public String getName()
	{
		return name;

	}

public int age()

	{	
		return age;
		
	}

public String type()

	{
		return type;
		
	}

public void setName(String newName)
{
	this.name = newName;
}

public void setAge(int newAge)
{
	this.age = newAge;
}

public void setLocation(String newLocation)
{
	this.location = newLocation;
}


}



