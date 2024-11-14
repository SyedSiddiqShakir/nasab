In this file, we define basic file storage format for entity recording

### Entity
Each node (person) in the graph can have the following attributes:

- **Unique ID**: A unique identifier for each person, which will help in linking nodes.
- **Name**: Full name of the person
- **Date of Birth**: To calculate age or display birth date
- **Estimated Age**: If exact birth date isn’t available
- **Date of Death**: For deceased persons
- **Gender**
- **Photo**: Optionally, you can store file paths or image data
- **Notes**: Any additional information, such as education, profession, etc.
- **Social_Credit**: Novel way of choosing favourite nodes