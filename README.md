# meumundo
#incluir <Ultrassônico.h>
#incluir <Servo.h>
#incluir "notas_musicais.h"

#definir pinoServo 7
#definir Trigonometria 2
#definir Eco 3
#definir B1A 8
#definir B1B 9
#definir A1A 10
#definir A1B 11

InteirodistanciaD;
InteirodistanciaE;
Inteiropino de campainha =6;

FlutuadordistanciaObstáculo =35;

Ultrassônicoutrassônico( Trig, Eco );

Servo servo;

Vazio Configurar ( ) {
Serial.começar (9600);

servo.anexar(pinoServo);
//Pinos da ponte H
Modo pin(B1A, SAÍDA);
Modo pin(B1B, SAÍDA);
Modo pin(A1A, SAÍDA);
Modo pin(A1B, SAÍDA);
Modo pin(buzzerPin, SAÍDA);

servo.escrever(90);
//Radar();
}

vazio laço() {j8u




