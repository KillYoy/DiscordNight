![](https://i.imgur.com/XQApc9q.png)

Requires [**Discord**](https://discordapp.com/) desktop app with [**BetterDiscord**](https://betterdiscord.app/) installed.

After installing BetterDiscord:
1. Download [**DiscordNight.theme.css**](https://betterdiscord.app/Download?id=155) and navigate to **Settings > Themes** and click on **Open Themes Folder** or place the file in **%appdata%/BetterDiscord/themes**
2. Refresh Discord using **CTRL+R** or restart Discord.
3. Go to **Settings > BetterDiscord > Themes** and enable **DiscordNight**.

- **Dark Theme** needs to be enabled in **Settings > Appearance > Theme** and select **Dark**.  

- BetterDiscord **Minimal Mode** is currently not supported.

Keep in mind that things may break at any time because of Discords background updates which may cause you to have to reinstall BetterDiscord or wait for the theme to be updated.  
Incase there is anything that has not yet been fixed or any plugin related issues feel free to either make a new [issue](https://github.com/KillYoy/DiscordNight/issues/new) or contact me **KillYoy#0295** on Discord.

This theme supports [**USRBG**](https://github.com/Discord-Custom-Covers/usrbg) by [**Tropical**](https://github.com/Tropix126).

# Preview
A comparison with and without the theme enabled:

![Main window comparision](https://i.imgur.com/fkQM8JW.png)
Matching colored underlines for member list roles requires the [**BetterRoleColors**](https://github.com/rauenzi/BetterDiscordAddons/tree/master/Plugins/BetterRoleColors) plugin.

![Settings comparision](https://i.imgur.com/5f6BjrR.png)

# Customizing the theme
DiscordNight has certain unique variables that can easily be modified to change the visibility and width of certain elements. The code can either be added to the **DiscordNight.theme.css** or the **Custom CSS** menu in Discord settings:

```css
:root {
	--User-List-Width: 200px;					          /* 200px, Discord default = 240px */
	
	--User-Popout-Width: 210px;					        /* 210px, Discord default = 250px */
	
	--Channel-List-Width: 196px;				        /* 196px, Discord default = 240px */
	--Channel-Invite-Edit-Button: none;			    /* flex = ON, none = OFF */
	--Channel-Category-Invite-Button: flex;		  /* flex = ON, none = OFF */
	
	--Search-List-Width: 488px;					        /* 488px, Discord default = 418px */
	
	--Inbox-List-Width: 522px;					        /* 522px, Discord default = 480px */
	
	--Titlebar-Help-Icon: none;					        /* flex = ON, none = OFF */
	
	--Chatbox-Gift-Button: none;				        /* flex = ON, none = OFF */
	--Chatbox-GIF-Button: none;					        /* flex = ON, none = OFF */
	--Chatbox-Stickers-Button: none;            /* flex = ON, none = OFF */
	
	--Chat-Emoji-Size: 1.75rem;					        /* 1.75rem, Discord default = 1.375rem */
	--Chat-Emoji-Large-Size: 2rem;				      /* 2rem, Discord default = 3rem */
	
	--Voice-Noise-Suppression: flex;		      	/* flex = ON, none = OFF */
	
	--Embed-Remove-Button: flex;			        	/* flex = ON, none = OFF */
	
	--Context-Menu-Emoji-Toolbar: none;		  	  /* flex = ON, none = OFF */
	
	--Home-Store-Button: none;			      		  /* block = ON, none = OFF */
	--Home-Direct-Messages-Header: flex;	  	  /* flex = ON with create DM Button, block = ON, none = OFF */
	--Home-Close-DM-Button: block;			      	/* block = ON, none = OFF */
	
	--Text-Channels-Capital-Letter: uppercase;	/* uppercase, none */
}
```

## Installing DiscordNight using other methods (Not recommended)
- If you don't want to use BetterDiscord or it does not work for some reason the CSS can be injected using Discords developer tools using **Ctrl+Shift+I** in the Desktop app or F12 in the browser. In the **Sources** tab go click on **assets** and find the file that ends with **.css** and paste in the code from **DiscordNight.css** into it, if done correctly the theme should be loaded until the next time Discord restarts (Keep in mind that images loaded from an external address will not load this way).

## Installing DiscordNight to your internet browser
- By using a stylesheet addon like Stylus, you can create a style for **discordapp.com** and paste in the code from **DiscordNight.css** (Not everything will work correctly like scrollbars and external images)
