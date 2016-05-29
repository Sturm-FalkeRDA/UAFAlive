- Place the Folder "Bullet_Casings" Inside your UserConfig folder.
- Your UserConfig Folder should be located in your Arma 3 Main Directory. ("C:\Program Files (x86)\Steam\SteamApps\common\Arma 3\UserConfig").
- If you do not have a UserConfig folder, then Create one.
- Edit the UserConfigFile.hpp to your own preferences.

Available Options:

#define USERSETTING_ConfigActive 1       	// nil = Disable Config      1 = Enable Config
#define USERSETTING_MaxCasingsAllowed 100       // Default = Max 100 empty casings at one time
#define USERSETTING_MaxCasingLifeTime 60*10     // Default = Max 10 minutes lifetime on each casing
#define USERSETTING_ApplyOnAllAI false         	 //  false = disabled for AI     true = enabled for AI