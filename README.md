# Object_Oriented_Programming_Project
This code is a turn-based, two player fighting game that works by acting on the 2 players input . The classes: BaseCharacter, Necromancer, Rogue, and Bruiser, make up the code. Inheritance, constructors, destructors, access specifiers (public, private, protected), method overloading, method overriding, and the implementation of getters and setters are some of the ideas used by these classes.
	* All characters' have common attributes, including name, health, attack, defense, and mana points, the first three you can enter, and are found in the BaseCharacter class, which acts as their parent class. Also, it implements virtual methods like attack, takeDamage, and specialAttack that may be overridden by derived classes, the BaseCharacter class offers getters and setters for accessing and altering the character's attributes, ensuring data integrity and encapsulation.
	* The undead_army_size attribute is added to the Necromancer class, which derives from the BaseCharacter class. The Necromancer may create an army of undead creatures with this function, which improves the BaseCharacter class when it uses its special ability, the move increases damage dealt and mana consumption in proportion to the army size. 
	* The arrows attribute is a addition to the Rogue class, which also descended from BaseCharacter. The class has a parameter for the number of arrows the class has. The quantity of arrows fired by the Rogue class's poisoned arrows is decreased with each attack by overriding the specialAttack method. The Rogue will switch to using a dagger if it runs out of arrows.
	* The rage attribute is a new addition to the Bruiser class, which derives from BaseCharacter. The Bruiser's rage level has two uses for special attacks and is not regenerable. When the anger level is high enough, the Bruiser class overrides the specialAttack function to launch its move Sword Spin.
	* When the user gives the necessary data, the code uses constructors to build objects and populate their properties. When an object is deleted, destructors are called to free up the memory that was reserved for it. By providing several iterations of the attack and specialAttack methods, each with a different parameter list or implementation, the code demonstrates method overloading.
	* Through setters and getters, we form a restrictive access to the 
classes’ attributes. These methods enable retrieval and modification of attribute values while preserving data encapsulation and integrity. The three classes collaborate to develop and engage in combat with various characters, offering a fun gaming experience while including crucial programming concepts.
