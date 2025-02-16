# data

Link to Project Presentation Video: <https://youtu.be/aEgNE4grw9c>

## Dataset 1: billionaires

-   `name`: The name of the billionaire.

-   `rank`: The rank of this billionaire compared to the rest of the billionaires reported on.
    A lower rank means they make more money.

-   `year`: The year that data about this billionaire was collected.

-   `company.founded`: The year that the company was founded.

-   `company.name`: The name of the company.

-   `company.relationship` : The billionaires relationship to the company.

-   `company.sector`: The sector of the business, or what segment of the economy they fit into.

-   `company.type`: The type of business for this company.

-   `demographics.age`: The current age of the billionaire.
    Ages that are represented as -1 stand for ages that were not available in the data that was collected.

-   `demographics.gender`: A string representing their gender.

-   `location.citizenship`: The name of the country that this billionaire has citizenship with.

-   `location.country code`: the 3-letter country code of the country where this billionaire has citizenship.

-   `location.gdp`: The "Gross Domestic Product" of the country where the billionaire has citizenship.
    This is one of the primary indicators used to gauge the health of a country's economy.
    It represents the total dollar value of all goods and services produced over a specific time period; you can think of it as the size of the economy.

-   `location.region` : The region of the world where this billionaire lives.

-   `wealth.type`: The type of billionaire that they are.

-   `wealth.worth in billions`: The number of billion of dollars that this billionaire is worth.

-   `wealth.how.category`: A category representing where their money came from.

-   `wealth.how.from emerging`: Whether the money came from emerging markets.

-   `wealth.how.industry`: The specific industry this billionaire profitted from.

-   `wealth.how.inherited`: The way that this money was inherited (or not inherited).
    Inheritance can come from a spouse, the father, or from multiple generations within a family (either 3, 4, or 5+).

-   `wealth.how.was founder`: Whether the billionaire was the founder of their company.

-   `wealth.how.was political`: Whether the money came from politics.

## Dataset 2: `fatal_police_shootings_data.csv`

-   `id` : a unique identifier for each victim

-   `name` : the name of the victim

-   `date` : the date of the fatal shooting in YYYY-MM-DD format

-   `manner_of_death` :

    -   shot

    -   shot and Tasered

-   `armed` : indicates that the victim was armed with some sort of implement that a police officer believed could inflict harm

    -   undetermined: it is not known whether or not the victim had a weapon

    -   unknown: the victim was armed, but it is not known what the object was

    -   unarmed: the victim was not armed

-   `age` : the age of the victim

-   `gender` : the gender of the victim.
    The Post identifies victims by the gender they identify with if reports indicate that it differs from their biological sex.

    -   M: Male

    -   F: Female

    -   None: unknown

-   `race` :

    -   W: White, non-Hispanic

    -   B: Black, non-Hispanic

    -   A: Asian

    -   N: Native American

    -   H: Hispanic

    -   O: Other

    -   None: unknown

-   `city` : the municipality where the fatal shooting took place.
    Note that in some cases this field may contain a county name if a more specific municipality is unavailable or unknown.

-   `state` : two-letter postal code abbreviation

-   `signs of mental illness` : News reports have indicated the victim had a history of mental health issues, expressed suicidal intentions or was experiencing mental distress at the time of the shooting.

-   `threat_level` : The threat_level column was used to flag incidents for the story by Amy Brittain in October 2015.
    http://www.washingtonpost.com/sf/investigative/2015/10/24/on-duty-under-fire/ As described in the story, the general criteria for the attack label was that there was the most direct and immediate threat to life.
    That would include incidents where officers or others were shot at, threatened with a gun, attacked with other weapons or physical force, etc.
    The attack category is meant to flag the highest level of threat.
    The other and undetermined categories represent all remaining cases.
    Other includes many incidents where officers or others faced significant threats.

-   `flee` : News reports have indicated the victim was moving away from officers

    -   Foot

    -   Car

    -   Not fleeing

The threat column and the fleeing column are not necessarily related.
For example, there is an incident in which the suspect is fleeing and at the same time turns to fire at gun at the officer.
Also, attacks represent a status immediately before fatal shots by police while fleeing could begin slightly earlier and involve a chase.

-   `body_camera` : News reports have indicated an officer was wearing a body camera and it may have recorded some portion of the incident.

-   `latitude and longitude` : the location of the shooting expressed as WGS84 coordinates, geocoded from addresses.
    The coordinates are rounded to 3 decimal places, meaning they have a precision of about 80-100 meters within the contiguous U.S.

-   `is_geocoding_exact` : reflects the accuracy of the coordinates.
    true means that the coordinates are for the location of the shooting (within approximately 100 meters), while false means that coordinates are for the centroid of a larger region, such as the city or county where the shooting happened.

## References

-   **Washington Post.** *Police Shootings Dataset*. GitHub, https://github.com/washingtonpost/data-police-shootings/blob/master/v1/README.md. Accessed 22 Oct. 2024.
