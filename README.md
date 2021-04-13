# gladius.app

## Site functionality 

You will choose a race when you create your gladiator. The race you belong to gives you bonus stats.  

### Social functions
	Add friends (friend request)
	Add enemies (someone has added you as enemy) 
	Guild (up to 16 people in a guild)
	Send letters (Either chat window or mailbox)

### Account
	Each account has at most one gladiator.
	If you want to “re-roll”, you must delete your current gladiator. 
	Authentication and authorization is done with auth0.
	
### Battle
	Weapon classes
		Crush, stab, slash, pummel, shield
	Armor 
		Defensive stats 1-10 damage reduction
		Weight varies (mail is heavy, leather is light) 
		More weight punishes your agility stats
	Stats
		Strength
			Endurance (allows you to fight longer)
			Health increased (increases health)
			Flat damage increased (increases weapon damage)
		Intelligence
			Speech (increases bargaining)
			Proficiency (increases exp gained from wins)
		Agility
			Weapon skill (increases chance to hit with weapons)
			Avoidance (can avoid attacks)
			Initiative (more likely to strike first)
			
### Duels
	Able to challenge other players to duels. 
	The winner of the duel gets x experience. 

Statistics
Amount of wins and losses.


## If there is time

These things may be implemented if we have time to do them 

### Quests 
	Daily quests
	Class advancement quests
	Earn race-specific skills
	
### Battle
	Jewelry 
		Your character can equip jewelry with certain stat bonuses

	When sending a duel request, you choose when to give up and what attack mode you want (offensive/defensive, hard hitting/light hitting) etc.
	The attack modes affect your strength and agility stats depending on your choices. 

# Technological specifications

## Front-end
	Angular
	
## Back-end/Server
	Flask
	
## Database
	sqlite
	
## Misc
	Auth0
	Postman
