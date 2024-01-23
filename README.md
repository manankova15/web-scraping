## Web Scraping Tutors Information from repetit.ru

This project involves web scraping tutor information related to mathematics from the repetit.ru website. The information collected includes details such as name, age, experience, education, star rating, verification status, price, subjects taught, total rating and the number of students.

### Code Explanation

The Python script utilizes the following libraries:

- **BeautifulSoup (bs4)**: for parsing HTML content.
- **requests**: for making HTTP requests to fetch web pages.
- **pandas**: for creating a DataFrame to store and manipulate the extracted information.

The script goes through multiple pages of the repetit.ru website, extracts links to individual tutor profiles, and then extracts detailed information about each tutor. Finally, the data is organized into a pandas DataFrame and exported to an Excel file.

### Output

The extracted information is saved in an Excel file named `tutors.xlsx`. The columns in the Excel file include:

- Name
- Age
- Experience
- Education
- Star rating
- Verification
- Price
- Subjects
- Total rating
- Students

