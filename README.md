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
