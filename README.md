public class DingDong {
    public static void multiples(){
        List<Integer> input = new List <Integer>{12,20,30,17};        
        for(Integer I:input){
            string Display1= 'Ding';
            string Display2= 'Dong';
            
            if (math.mod(I,3) ==0 && math.mod(I,5) ==0){
                system.debug(Display1+Display2);
            }
                else if (math.mod(I,3)==0){
                    system.debug(Display1);
                    
                }
            else if(math.mod(I,5)==0){
                system.debug(Display2);
            }
            else{
                system.debug(I);
            }
        }
