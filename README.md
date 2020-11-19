## Habitude

![img](screenie.png)

A gamified "progress tracker" widget for your habits or anything you want to do daily !

Pre-alpha-here-be-dragons edition. Still figuring ideas, not much set in stone (such as life !) :)

## Usage

#### Linux

    ./habitude

Press 'K' to exit

#### Windows

    habitude.exe

Press 'K' to exit

#### Config file format

You need to have a file called **config.json** with this format in the **same folder** you run habitude

	{
	  "Description1": "20 Squats + 12 Push-ups",
	  "Description2": "No pecking your nose",
	  "Quote": "Waste no more time arguing what a good man should be. Be one",
	  "QuoteAuthor":"- Marcus Aurelius",
	  "DaysCounter": 2,
	  "RankTitle": "\"Super Hero Cadet\"",
	  "Updated": "As of 19 Nov 2020"
	}

#### Background image

Put a file named background.png in the folder where you run habitude, it needs to be 800x450

#### Sidenote : Compile for Windows

    GOOS=windows GOARCH=amd64 go build

#### Sidenote : Artwork

Credits goes to Square Enix for Final Fantasy XV Pocket Edition
Credits goes to Blizzard for Starcraft Icons

Don't sue me okay ? :D