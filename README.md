# Soumyadip
public class Doctor extends Person // inherit name from Person in Doctor class
{
//inlcude the required attribute and method as per the problem statement
        String specializationType;
        
        void setName(String str){
            this.name = str;
        }
        
        String getName(){
            return this.name;
        }
        
        void setSpecializationType(String str){
            this.specializationType = str;
        }
        
        String getSpecializationType(){
            return this.specializationType;
        }
        
        String displayDetails(){
            String ans = getName() + " is a " + getSpecializationType();
            return ans;
        }

}
