# What's the goal of the app?
Replace Grafik KDM główny (Google Sheet), and other apps (spotdomy, karta kontaktowa), for a centralised system.

- **Modules**
	- Ministries (will replace Grafik KDM główny)
		- Uses `Ministry` model
		- View a specific person's roles per week — *What am I (or John, Mary, and Bob) on this week?*
		- View a specific role's assigned people per week — *Who is on Tech Media (or Zespol) this week?*
		- Roles
			- Uses `Role` model
	- Contacts (will replace https://kdm.formstack.com/forms/karta_kontaktowa)
		- Uses `Person` model
		- Will be like apple contacts
	- Spotdomy reports (will replace https://kdm.formstack.com/forms/spotdomy)
		- Uses `Spotdomy report` model
		- Create, edit, and view reports
- **Models**
	- Ministry
		- Name
		- Manager
		- Roles
		- Color
		- Logo
	- Role
		- Name
		- People assigned
		- Color
	- Person
		- First name
		- Last name
		- Email
		- Phone
		- District
		- Language
		- Category
		- How they found us
		- Additional information
		- Spotdomy
		- Receive newsletter
		- Who found them
		- Date
	- Spotdomy
		- Leaders
		- People
		- Location
		- Start time
		- Color
		- Logo
	- Spotdomy report
		- Associated Spotdomy
		- People from associated Spotdomy and others
		- Number of people (generated automatically)
		- Summary
		- Challenges
		- Person who made the report
		- Date
