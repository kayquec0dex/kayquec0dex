```python
class Attributes(Tekky):
	def __init__(self) -> None:
	    pass
	
	@staticmethod
	def contact(self) -> tuple:
	    discord  = "tekky#2229"
	    telegram = "t.me/xtekky"
	    proton   = "xtekky@protonmail.com"
	    
	    return discord, telegram, proton
	
	@staticmethod
	def life(self) -> tuple:
		langs         = ['French', 'German', 'Spanish', 'English']
		nationalities = self.langs.remove('French', 'English').append('Korean')
		age           = 17
		
		return langs, nationalities, age
	
	@staticmethod
	def coding(self) -> tuple:
		langs = {
			'expert':   ['python'],
			'intermediate': ['go', 'js'],
			'learning': ['c', 'c++', 'c#', 'asm', 'java']
		}
		specialities  = ['web/app reverse engineering', 'fullstack', 'skidding (joke)']
		environnement = ['vscode', 'pycharm']
		
		return langs, specialities, environnement
	
	@staticmethod
	def projects(self) -> tuple:
		discord   = ['HQ Gen', 'Raid Toolkit']
		tiktok    = ['view bot', 'Algorithms']
		instagram = ['Gen', 'Botting']
		twitch    = ['Free Gen', 'Everything u can think of']
		website   = ['tikstats.io', 'tikbotting.com']
		
		return discord, tiktok, instagram, twitch, website

```
