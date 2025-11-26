public class Emp Comparable

{

int id;

String name;

double sal;

public Emp(int id,String name,double sal)

{

Super();

this.id=id;

thid.name=name;

this.sal=sal;

}

public String toString()

{

return "Emp\[id="+id+",name="+name+",sal="+sal+"]";



public int compare to(object o)

{

Emp e=(Emp )0;

if(this.sal>e.sal)

return 1;

else if(this.sal<e.sal)

{

return -1;

}



else

return 0;

}

}

}



public class Array1{

public static void main(String\[] rags)

{

Emp\[] e=new Emp\[5];

e\[0]=new Emp(101,"allen",1000);

e\[1]=new Emp(102,"Smith",2000);

**e\[2]=new Emp(103,"adams",3000);**

**e\[3]=new Emp(104,"jack",4000);**

**e\[4]=new Emp(105,"miller",5000);**

**Array.sort(e)**

**for(int i=0;i<e.length;i++)**

**{**

**System.out.println(e\[i]);**

**}**

**}**

**}**



