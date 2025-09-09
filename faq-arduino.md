# Preguntas frecuentes sobre Arduino (S4AEDU)

## Planificación
**¿Qué conocimientos previos requiere el docente para utilizar la tarjeta S4AEDU con su grupo de estudiantes?**  
Se requiere tener un conocimiento base en el uso de la tarjeta, así como conocimiento operativo (reconocer los sensores y actuadores y su conexión con la tarjeta) y funcional en programación con el IDE de Arduino.

---

## Implementación
**¿Qué debo hacer si la tarjeta S4AEDU no es reconocida por la computadora?**  
- Verifique que el cable USB sea funcional.  
- Revise que el puerto COM aparezca en el Administrador de dispositivos.  
- Verifique que se haya instalado el controlador CP210x desde:  
  [Controlador CP210x](https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers)  
- Consulte el protocolo completo compartido antes del taller o disponible en la MiniWeb (Preparando el Equipaje).

**¿Cómo pruebo que la tarjeta está funcionando correctamente?**  
1. Abra el IDE de Arduino.  
2. Configure la placa como “Arduino UNO” o “Duemilanove Diecimila” y seleccione el puerto COM correcto.  
3. Abra `Archivo > Ejemplos > 01.Basics > Blink`.  
4. Cargue el programa.  
5. Si el LED integrado parpadea, la tarjeta funciona correctamente. Si no, consulte el protocolo completo en la MiniWeb (Preparando el Equipaje).

**¿Puedo conectar cualquier sensor o actuador a cualquier pin de la placa?**  
Se deben respetar el tipo de señal (analógica o digital) y polaridad, aunque GND y VCC (V+) son compartidos.

**¿Cómo se organiza la programación en Arduino?**  
En tres partes generales:  
1. **Declaración de variables**  
2. **setup()**  
3. **loop()**
