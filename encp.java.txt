class Encapsulation_NameExample{
        private String Name;
        
        //Geter Funcation or NoSuchMethod
        
        public String get()
        {
            return Name;
        }        
        //Setter Funcation
        public void set(String NameRecived_to_set)
        {
            this.Name = NameRecived_to_set;
        }
}
public class Main
{
	public static void main(String[] args) {
	    System.out.println("Name By detfault is before calling get method");
	    Encapsulation_NameExample MyName = new Encapsulation_NameExample();
	    System.out.println("Recived name by default is" + MyName.get());
	    MyName.set("Avinash");
	    System.out.println("Recived name after setting name" + MyName.get());
	    System.out.println("Now if we are here it mean our program is working fine and we we are good here");
	}
}
