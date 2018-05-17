The following are exercises for product positions.

## **Title: Product Roadmap/Positioning - Work Exp - Tech**

- **Overview:** In this interview, you are assessing if the candidate has the ability to work well with a Cockroach Labs engineering team to define, communicate, and deliver on a feature roadmap. At this level, candidates may focus on the smaller picture, so the emphasis is placed on the ability to execute against a roadmap, influence and collaborate with internal/external technical stakeholders, and make principled tradeoffs in order to deal with technical or market realities.

- **Setup:** Candidate will be asked by the recruiter to pick a product (or feature) that they took through to launching to the public. The preference is that they use a product that had technology clients (as opposed to marketing or another department). They will be prepared to discuss the product (or feature) with you.

- **Part 1:** Work Experience - Ask them to dive into their product/feature from a technical standpoint. They should be able to speak to the technical details in this section. How did the product evolve? From concept to launch or was it pre-existing? 

## **Title: Ops and Tools PM Takehome Exercise: MySQL Migration**
- **Overview** One of the most important things we can do to drive adoption is to make database migrations frictionless. In this exercise, you will migrate a single table from MySQL to CockroachDB and describe how this process can be improved. This entire exercise should take under an hour.  
- **Setup**   
    - [Start a single-node CockroachDB cluster](https://www.cockroachlabs.com/docs/stable/start-a-local-cluster.html).    
    - [IMPORT](https://www.cockroachlabs.com/docs/stable/import.html) the [MySQL CSV export file](https://raw.githubusercontent.com/cockroachlabs/open-sourced-interview-process/master/files/product/employees.csv) into CockroachDB (*we've provided a standard CSV file rather than the raw [mysqldump](https://dev.mysql.com/doc/refman/8.0/en/mysqldump.html) output. No modifications are necessary*).
    - Hints: 
        - For IMPORT to work, you'll need to Convert [the original MySQL schema](https://raw.githubusercontent.com/cockroachlabs/open-sourced-interview-process/master/files/product/employees.mysql.sql) into a [Cockroach CREATE statement](https://www.cockroachlabs.com/docs/stable/create-table.html#main-content). 
        - Be sure to create a database before you begin the IMPORT. Example SQL: `CREATE DATABASE exercise; USE exercise;`

- **Exercise**
    1. What are some of the shortcomings of this migration experience? 
    1. In a sentence or two, describe an enhancement that would make the migration process delightful for developers.
    1. Write 2-3 [user stories](https://www.mountaingoatsoftware.com/agile/user-stories) to further explain this feature. It's OK if the entire feature isn't covered in 2-3 stories.
    1. How would you validate this feature?


## **Title: Geneal PM Takehome Exercise: Product Positioning**
- **Overview** In addition to traditional product management responsibilities, Cockroach Labs PMs are also responsible for positioning their features and producing raw content that can be leveraged by marketing and sales to help promote those enhancements. This exercise is meant to help us understand how PMs think about audiences, differentiation, and value creation. 

- **Setup** Pick any feature from a B2B company and write a one page messaging framework about it. This should at least include: a positioning statement, target audience, elevator pitch, and three messaging pillars. You can read more about messaging frameworks on Google. (Here’s an example from Salesforce to get you started).

## **Title:** **Product Roadmap - New/CRL Specific**

- **Overview:** In this interview, you will be getting a sense of how well the candidate understands the basic aspects of product management and how passionate they are about the discipline.

- **Setup:** In three minutes or less, walk me through your favorite B2B product.

## **Title:** **Analytical Case**

- **Overview:** Provide the candidate with this  [excel spreadsheet](https://docs.google.com/spreadsheets/d/12f3kjlTs5QpCmsvXo-ZLOWG5rFdc4DaB6TwJxoQxVOE/edit#gid=0) of fictional telemetry and have them pull insights. 

- **Exercise:** Expectations are for the candiate to navigate the data and visualize it in a way that tells a story of adoption (or lack thereof). 

   
## **Title:** **Whiteboarding Customer Experience**

- **Overview:** In this interview, you are focusing on the candidate’s ability to understand customer pain points in an enterprise environment and collaborate with design + engineering to create solutions they love. Product Managers have to know (and have frequent contact and communication with) their customers and users. Successful PMs should incorporate real world customer needs and feedback into product development and go beyond the UI when thinking about user experience.

- **Exercise:** We have a new product design prototyping tool that designers use to share mocks with other stakeholders. We need a way to onboard new users. The goal is to provide user stories or user flows that outline this process. 

- **Interview Flow** 
    1. Context/Discovery - there is a SaaS product for collaborating with design - 5 minutes
    
    2. Framing: Goals/Audience - what are you optimizing for and for whom? - 5 minutes
    
    3. Tactical execution - what is the actual flow or user stories - 30 minutes

    4. Edge cases - 10 mins

    5. Validation - How can you validate that your solution meets the goals we mentioned earlier? - 10 mins
