# Kalkulator
public class reni extends javax.swing.JFrame {
double nilai1,nilai2;
   public reni() {
        initComponents();
    }

        void penjumlahan(){
          
            int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
            
            int penjumlahan = Nilai1+Nilai2;
                    
             jLabel3.setText("hasil = "+penjumlahan);
        }
        void pengurangan(){
             int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
         
            int pengurangan = Nilai1-Nilai2;
            
            jLabel3.setText("hasil = "+pengurangan);
        }
        void perkalian(){
            int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
            
            int perkalian = Nilai1*Nilai2;
            
            jLabel3.setText("hasil ="+perkalian);
        }   
         void pembagian(){
             double Nilai1=Double.parseDouble(jTextField1.getText());
             double  Nilai2=Double.parseDouble(jTextField2.getText());
            
             double pembagian = Nilai1/Nilai2;
            
            jLabel3.setText("hasil ="+pembagian);
             }
   private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         
pembagian();        
    }                                        

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
penjumlahan();   
    }                                        

    private void jTextField1ActionPerformed(java.awt.event.ActionEvent evt) {                                            
     
    }                                           

    private void jTextField2ActionPerformed(java.awt.event.ActionEvent evt) {                                            
       
    }                                           

    private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         
pengurangan();        
    }                                        

    private void jButton4ActionPerformed(java.awt.event.ActionEvent evt) {                                         
perkalian();        
    }                                        
  
