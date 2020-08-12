# Final Project - Mehak Sharma

The data I looked at for this project is for COVID-19 vaccines and treatments. This data was obtained from [the Milken Institute's COVID-19 Tracker](https://covid-19tracker.milkeninstitute.org/). The Milken Institute’s FasterCures project is tracking hundreds of potential COVID-19 treatments and vaccines. For each candidate, the project’s database lists its category (e.g., DNA-based vaccines, cell-based therapies, et cetera), a brief description, its stage of development, “anticipated next steps,” funders, published results, FDA-Approved indications, and more.

[Link to data](https://airtable.com/shrSAi6t5WFwqo3GM/tblEzPQS5fnc0FHYR/viweyymxOAtNvo7yH?blocks=bipZFzhJ7wHPv7x9z)

For most of these fields, not much cleaning was needed. I noticed some count errors while making pivot tables, which I then fixed by "trimming" certain values as there was an extra space at the end of the value, which prevented it from being categorized and  counted correctly.

<h3>Initial Data Exploration</h3>

![Data-Filtering](https://github.com/mehak00/data_journalism/blob/master/covid-19-vaccine-tracker/data-interrogation.png)

I began exploring the data by putting filters on fields I thought may show interesting results, specifically the category types (e.g., DNA-based vaccines, cell-based therapies, et cetera) and the development stages. After filtering for certain types and stages, I took a look at the different product descriptions, FDA indications, and funders, to get a better sense of the landscape. Through this initial exploration, I was able to see a correlation between the category types and development stages, which I decided to further explore using other methods.

<h3>Breakdown by Vaccine/Treatment Category</h3>

![Vaccine/Treatment Categories - Pie Chart](https://github.com/mehak00/data_journalism/blob/master/covid-19-vaccine-tracker/breakdown-by-catagory.png)

<h3>Relationship between Category and Development Stage</h3>

I created a pivot table to visualize the relationship between category and development stage.

![Category and Development Stage - Pivot Table](https://github.com/mehak00/data_journalism/blob/master/covid-19-vaccine-tracker/category-development-pivot.png)

Some additional data I made efforts to find for this project including more information about the funding - Operation Warp Speed, as well as other global funders. Unfortunately, I was unable to find a comprehensive dataset on any of these topics.
