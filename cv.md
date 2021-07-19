# *HORBATSEVICH TATSIANA* #

## Contacts:
e-mail: gtatsiana@tut.by

tel: +375(29)345 82 84

## Summary of Qualifications
- Good theoretical knowledge of software testing process.
- Good understanding of Scrum methodology.
- Basic knowledge of JS,JAVA
- Experience in test documentation design and update: test cases, check lists.
- Detail oriented, methodical deal with routine, hardworking, responsible, well-organized, sociable and fast learner. 
- Capable of working in a multitasking mode, making decisions under difficult and stressful conditions.
## Technical Skills
- Operating Systems: Windows XP/7/8/10, Android, iOS
- Bug tracking system: Jira, Azure DevOps
- Browsers: Chrome, Firefox, Edge, Internet Explorer
- Testing tools: Postman, Dev Tools, Charles, Web Console
- Database: MySQL
- Test Management tool: TestRail, Google docs
- Development Environments and Tools: Visual Studio Code, IntelliJ IDEA 
- Source Control: Git
- Professional Experience
## Examples of code

  function getSimpsonsQuoteFromApi() {
  
  const url = "https://simpsons-quotes-api.herokuapp.com/quotes/";
  
            axios.get(url)
                .then(function(response) {
                    return response.data;
                })
                .then(function(simpsonsQuote) {
                    console.log('data decoded from JSON:', simpsonsQuote);
                    const simpsonQuoteHtml =
                        `<p><strong>Name: ${simpsonsQuote[0].character}</strong></p>
                        <p><strong>Quote: ${simpsonsQuote[0].quote}</strong></p>
                        <p>Avatar:</p>
                        <img src="${simpsonsQuote[0].image}" alt ="simpsons picture"/>`;

                    document.querySelector("#simpson").innerHTML = simpsonQuoteHtml;
                });
        }
### Professional Certificates
- Training courses for beginner testers from Exadel, 2020	 
- Internal QA training for junior Qas, 2021 		
- 'Front-End Web Development' Wild Code School, 2021		
- 'Java for beginners' Udemy, 2021								
### Education
Sample University:	2005

Belorussian Technological University,

process engineer of printing production
### Professional Experience
- EXADEL, Junior QA 01.2021 - present
- structural unit of the KGB, engineer 07.2020 - 08.2020
#### *English level:* B1



