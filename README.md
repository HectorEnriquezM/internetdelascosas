# internetdelascosas
//SIMULADIR DE UN SEMAFORO//
Internet de las cosas
// C++ code
//
void setup()
{
  pinMode(9, OUTPUT); //Led Rojo
  pinMode(8, OUTPUT); //Led Ambar
  pinMode(7, OUTPUT); //Led Rojo
}

void loop()
{
  digitalWrite(7, HIGH); //Encender Led verde
  delay(6000); // Esperamos 6 seg. encendido
  digitalWrite(7, LOW); //Lo apagamos 
  delay(500); // Esperamos .5 segundos
  
  
  digitalWrite(8, HIGH); //Encender Led Ambar
  delay(500); // Esperamos 6 seg. encendido
  digitalWrite(8, LOW); //Lo apagamos 
  delay(500); // Esperamos .5 segundos
  
  digitalWrite(8, HIGH); //Encender Led Ambar
  delay(500); // Esperamos 6 seg. encendido
  digitalWrite(8, LOW); //Lo apagamos 
  delay(500); // Esperamos .5 segundos
  
  digitalWrite(8, HIGH); //Encender Led Ambar
  delay(500); // Esperamos 6 seg. encendido
  digitalWrite(8, LOW); //Lo apagamos 
  delay(500); // Esperamos .5 segundos
  
  digitalWrite(8, HIGH); //Encender Led Ambar
  delay(500); // Esperamos 6 seg. encendido
  digitalWrite(8, LOW); //Lo apagamos 
  delay(500); // Esperamos .5 segundos
  
  digitalWrite(8, HIGH); //Encender Led Ambar
  delay(500); // Esperamos 6 seg. encendido
  digitalWrite(8, LOW); //Lo apagamos 
  delay(500); // Esperamos .5 segundos
  
  digitalWrite(9, HIGH); //Encender Led Rojo
  delay(6000); // Esperamos 6 seg. encendido
  digitalWrite(9, LOW); //Lo apagamos 
  delay(500); // Esperamos .5 segundos
  
  
}
