Java-DNA-Fun
============

This is by far one of my most favorite projects. Seeing how the medical field can correlate with computer programming thrills me. This specific algorithm returns how many  of each different nucleobases are present in the given DNA strand. 
/**
 * Write a description of class DNAProgram here.
 * 
 * @author (your name) 
 * @version (a version number or a date)
 */
public class DNAProgram
{
public static int a, t, g, c =  0;
public static void main (String args [])
   
    {
        
        char [] bases = {'A','C','A','T','T','C','C','T','A','C','C','T','T','G','C','C','C','A','C','C'};
               
    
        
        for (int i = 0; i<20; i++){
        
            System.out.println("DNA Strand :" +bases[i]);
        

            if (bases[i] == 'A')
            a ++;
           
        
    
      if (bases[i] == 'C')
       c ++;
      
    
    
        if (bases[i] == 'T')
        t ++;
       
    
    
    
        if (bases[i] == 'G')
        g ++;
        
    }
    {
       System.out.print("adenine : " +a);
       System.out.println();
       System.out.print("cytosine : " +c);
       System.out.println();
       System.out.print("thymine : " +t); 
       System.out.println();
       System.out.print("guanine: " +g);
        System.out.println();
       
    }
            
}    
}
