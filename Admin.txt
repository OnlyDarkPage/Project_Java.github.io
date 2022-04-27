public class Admin extends User{
    private final boolean isAdmin = true;
    
    public Admin(String name, String phone){
        this.name = name;  
        this.phone = phone;
    }
}
