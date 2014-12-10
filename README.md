logisim-evolution
=================
Logisim is an educational tool for designing and simulating digital logic circuits.
It has been originally created by [Dr. Carl Burch](http://www.cburch.com/logisim/) and actively developed until 2011.
After this date the author focused on other projects, and recently the development has been officially stopped  [(see his message here)](http://www.cburch.com/logisim/retire-note.html).

In the meantime, people from a group of swiss institutes ([Haute École Spécialisée Bernoise](http://www.bfh.ch), [Haute École du paysage, d'ingénierie et d'architecture de Genève](http://hepia.hesge.ch), and [Haute École d'Ingénierie et de Gestion du Canton de Vaud](http://www.heig-vd.ch)) started developing a version of Logisim that fitted their courses, integrating several tools -- for instance a chronogram, the possibility to test the schematics directly on an electronic board, TCL/TK consoles, ...

The project is currently maintained by the [REDS Institute](http://reds.heig-vd.ch), which is part of the [Haute École d'Ingénierie et de Gestion du Canton de Vaud](http://www.heig-vd.ch), Yverdon-les-Bains, Switzerland.

We have decided to release this new Logisim version under the name logisim-evolution, to highlight the large number of changes that occurred in these years, and **we actively seek the contribution of the community**.

## What's new in logisim-evolution
* Chronogram -- to see the evolution of signals in your circuit
* Electronic board integration -- schematics can now be simulated on real hardware!
* Board editor -- to add new electronic boards
* VHDL component -- a new component type whose behavior is specified in VHDL
* TCL/TK console -- interfaces between the circuit and the user
* DIP switches
* RGB LEDs
* large number of bug-fixes
* GUI improvements
* code refactoring
* ...

## How to install logisim-evolution
To use logisim-evolution you simply need to clone the repository on your local machine. Once this is done, enter the directory and execute
```bash
ant run
```
This also creates locally a .jar file, that you can distribute and use on other machines, executing it directly with
```bash
java -jar logisim-evolution.jar
```
## How to get support for logisim-evolution
Unfortunately, we do not have enough resources to provide direct support for logisim-evolution.
We will, however, try to deal with the raised issues in a *best-effort* way.

If you find a bug or have an idea for an interesting feature, please do not hesitate to open a ticket!

## Other Logisim forks available on the net
* Logisim by Joseph Lawrance et al. [(link)](https://github.com/lawrancej/logisim) - they have started from Burch's original code and integrated it in several open-source development frameworks, cleaning up the code. We have taken a few code cleanups and the redo functionality from their code.
* logisim-iitd [(link)](https://code.google.com/p/logisim-iitd) - IIT Delhi version of Logisim, it integrates the Floating-Point Components within the Arithmetic Unit.