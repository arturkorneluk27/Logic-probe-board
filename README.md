🇵🇱Polish version
# Próbnik stanów logicznych
  
    Odtworzenie gotowej płytki PCB w programie KiCad na zasadach reverse engineering.
    
# Opis projektu

Podczas laboratorium "Montaż Systemów Elektronicznych" wykonałem ręczny montaż próbnika stanów logicznych
z wykorzystaniem technologii SMD oraz lutowania bezołowiowego.

Po zakończeniu zajęć postanowiłem odtworzyć projekt płytki w programie KiCad.
Na podstawie gotowego urządzenia wykonałem schemat ideowy oraz projekt PCB,
starając się możliwie wiernie odwzorować oryginalny układ, rozmieszczenie
elementów oraz prowadzenie ścieżek.

Projekt miał na celu rozwinięcie umiejętności projektowania schematów i płytek PCB w KiCadzie oraz analizowania działania układów cyfrowych.

# Funkcjonalność 

Próbnik umożliwia wykrycie:
- 🟢 stanu logicznego LOW
- 🔴 stanu logicznego HIGH
- 🔵 zbocza opadającego FALL
- 🟡 zbocza narastającego RISE 
  
Sygnalizacja realizowana jest za pomocą czterech diod LED.

# Zastosowane układy

- LM358 - podwójny wzmacniacz operacyjny pracujący jako komparator napięcia
- HEF4001 / CD4001 - układ czterech bramek NOR

# Narzędzia

- KiCad
- Git / Github

# Etapy projektu

1. Odtworzenie schematu ideowego
2. Dobór symboli i footprintów elementów
3. Zaprojektowanie PCB
4. Odtworzenie rozmieszczenia elementów
5. Odtworzenie przebiegu ścieżek na podstawie fizycznej płytki

# Pliki projektu
- `probnik.kicad_sch` - schemat ideowy
- `probnik.kicad_pcb` - projekt płytki PCB
- `probnik.kicad_pro` - plik projektu KiCad


<br><br>
---


🇬🇧English version

# Logic State Probe

    Recreation of an assembled PCB in KiCad using reverse engineering techniques.

# Project description

During the "Electronic Systems Assembly" lab, I manually assembled
a logic state probe using SMD technology and lead-free soldering.

After completing the lab, I decided to recreate the PCB design in KiCad.
Based on the finished device, I drew the schematic and designed the PCB,
aiming to faithfully reproduce the original circuit, component placement,
and trace routing.

The goal of the project was to develop schematic and PCB design skills
in KiCad and better understand how digital circuits work.

# Features

The probe can detect:
- 🟢 logic LOW state
- 🔴 logic HIGH state
- 🔵 falling edge FALL
- 🟡 rising edge RISE

Each state is visualised by a dedicated LED.

# Components used

- LM358 - dual op-amp operating as a voltage comparator
- HEF4001 / CD4001 - quad NOR gate IC

# Tools

- KiCad
- Git / Github

# Project stages
1. Recreating the schematic
2. Selecting symbols and footprints
3. Designing the PCB layout
4. Reconstructing component placement
5. Reconstructing PCB trace routing based on the physical board

# Project files
- `probnik.kicad_sch` - schematic
- `probnik.kicad_pcb` - PCB layout
- `probnik.kicad_pro` - KiCad project file
