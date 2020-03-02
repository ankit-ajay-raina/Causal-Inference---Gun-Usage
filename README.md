# Causal-Inference---Gun-Usage
CAUSAL INFERENCE: UNDERSTANDING EFFECTS OF GUN USAGE ON CRIME RATE

The right-to-carry laws, or shall-issue laws, is one of the most hotly debated laws in America. A Shall-issue law is one that requires that governments issue concealed carry-handgun permits to any applicant who meets the following necessary criteria:
•	The applicant must be an adult
•	Applicant must have no significant criminal record and no history of mental illness
•	Applicant must successfully complete a course in firearms safety training (if required by law)

If the above criteria are met, the applicant is eligible to be issued a handgun permit and is not required to demonstrate ‘good cause’. This has sparked off a debate with some claiming that the move would make citizens better equipped to handle crime/ attacks and fend off potential attackers, while others feel that the move would make it easier for potential criminals to access weapons or that it may raise the number of accidental crimes.

Guns is a balanced panel of data on 50 US states, plus the District of Columbia (for a total of 51 “states”), by year for 1977 – 1999. Each observation is a given state in a given year. There is a total of 51 states × 23 years = 1173 observations. 

Objective: To analyze historical data on crime in the U.S to answer the questions: 
	“Do shall-issues law reduce crime-or not?”
	“Does incarceration policy reduce crime-or not?”  


Variable	Definition
vio	: violent crime rate (incidents per 100,000 members of the population)
rob	: robbery rate (incidents per 100,000)
mur	: murder rate (incidents per 100,000)
shall	= 1  : if the state has a shall-carry law in effect in that year 
= 0 otherwise
incarc_rate	: incarceration rate in the state in the previous year (sentenced prisoners per 100,000 residents; value for the previous year)
density	: population per square mile of land area, divided by 1000
avginc	: real per capita personal income in the state, in thousands of dollars
pop	: state population, in millions of people
pm1029	: percent of state population that is male, ages 10 to 29
pw1064	: percent of state population that is white, ages 10 to 64
pb1064	: percent of state population that is black, ages 10 to 64
stateid	: ID number of states (Alabama = 1, Alaska = 2, etc.)
year	: Year (1977-1999)
