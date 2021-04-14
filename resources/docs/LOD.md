# Law of Demeter (LoD)

extracted from [wikipedia](https://en.wikipedia.org/wiki/Law_of_Demeter)

<img src="../images/LOD.jpg" align="left"  width="200" />

**The Law of Demeter (LoD)** or **principle of least knowledge** is a design guideline for developing software, particularly object-oriented programs. 

In its general form, the **LoD** is a specific case of loose coupling. The guideline was proposed by Ian Holland at Northeastern University towards the end of 1987. It is so named for its origin in the Demeter Project, an adaptive programming and aspect-oriented programming effort. <br /><br />

* Each unit should have only limited knowledge about other units: only units "closely" related to the current unit.
* Each unit should only talk to its friends; don't talk to strangers.
* Only talk to your immediate friends.
