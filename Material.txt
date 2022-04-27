public class Material extends Entity{
    private final double level1;
    private final double level2;
    private final double level3;
    
    public Material(String name, String description, int id, double level1, double level2, double level3){
        this.name = name;
        this.description = description;
        this.id = id;
        this.level1 = level1;
        this.level2 = level2;
        this.level3 = level3;
    }
    
    public double getLevel1(){
        return this.level1;
    }
    
    public double getLevel2(){
        return this.level2;
    }
    
    public double getLevel3(){
        return this.level3;
    }
    
    public String getDetails(){
        return "Type of Entity: Material\n" + "Level1: " + this.level1 + " pieces\nLevel2: " + this.level2 + " pieces\nLevel3: " + this.level3 + " pieces";
    }
}
