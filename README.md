# Retro-sound
a project i made which i can call the simplest specker to exist, uses a passive buzzer with aurdinio to make sounds and play retro songs. it can also play some modren songs as long as it is simple. It is compatable on all aurdinios which have the tune function 

this is a tool you can use to convert any midi file into code for the buzzer https://tawsiftorabi.github.io/Midi2ArduinoTone/

i have also attched the tools files if you want to install it locally

#making it work
  1. simply follow the wiring diagram (its really simple)
  2. install the midi to code tool or use the link provided
  3. by defualt it will only play the song one if you want to make it loop then
        change the code at the end
     
     void setup() {
  // Nothing here
}

void loop() {
  song(11);   // Repeats forever 

  also 11 is the pin feel free to change it.


#coming soon
exe file for tool
a case you can 3d print and have a cool little gadget
