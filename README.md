# meu-projeto
#incluir <Servo. h>
#incluir notas_musicais.h

#definir pinoServo 7
#definir Trigometria 2
#definir Eco 3 
#definir B1A 8
#definir B1B 9
#definir A1A 10
#definir A1B 11

 InteirodistanciaD;
 InteirodistanciaE;
 Inteiropino de campainha =6;

 flutuadordistanciaObstáculo =35;

 Ultrassônicoultrassônico(Trig, Eco);

 Servo servo;

  vazio configurar() {
   Serial.começar(9600);

   servo.anexar(pinoServo)
  //pinos da ponre H 
  Modo pin(B1A, SAÍDA);
  Modo pin(B1B, SAÍDA);
  Modo pin(A1A, SAÌDA)
  Modo pin(A1B, SAÌDA);
  Mdo pin (buzzerPin, SAÌDA);

  servo.escrever(90);
  //Radar();
  {

  ^ vazio laço() {

     Serial.imprimir(ultrassônico.Alcance(

     se(ultrassônico.Alcance(CM) <= distância
       Andar(5);
         Inteirostatus =Radar();
         atraso(500);
         se(estado ==1){
           Andar(2);
           atraso(600);
           Andar(4);
           atraso(400);
           Andar(5);
         }
          se(estado ==2) { 
           Andar(2)
           atraso(600);
           Andar(3);
           atraso(400);
           Andar(5);
          }
           se(estado ==0) {
             Andar(2);
             atraso(500);
             Andar(4);
             atraso(300);
             Andar(5);
            }
             atraso(1000);
          }
        outro{
           Andar(1);
        }
      }
       
