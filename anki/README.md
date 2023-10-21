### Anki Best Practices and Installation Guide

#### Installation Guide

1. **Download Anki**: Visit the [Anki website](https://apps.ankiweb.net/) and download the version compatible with your operating system.
2. **Install Anki**: Run the downloaded file and follow the installation instructions.
3. **Open Anki**: Once installed, open Anki and you'll be presented with the main interface.
4. **Create a New Deck**: Click on "Create Deck" at the bottom and give it a name related to AWS Certification.

> **Tip**: Don't download the mobile app; it's expensive. You can use the browser version on your phone.

#### Examples of Three Different Types of Anki Cards

1. **Basic Card**
    - **Front**: What is AWS S3?
    - **Back**: AWS S3 (Simple Storage Service) is a scalable object storage service for storing and retrieving data.

2. **Cloze Deletion Card**
    - **Text**: AWS {{c1::S3}} is a scalable {{c2::object storage service}}.
    - **Result**: Two cards are created. One with "AWS [...]" and the other with "is a scalable [...]."

3. **Image Occlusion Card**
    - **Image**: Diagram of AWS architecture
    - **Occlusions**: Cover the names of AWS services in the diagram.
    - **Result**: Cards that reveal each AWS service in the diagram when reviewed.

> **Note**: Image Occlusion cards require the Image Occlusion Enhanced add-on, which can be downloaded within Anki.

#### Storing Anki Decks in GitHub

1. **Export Deck**: In Anki, click on the deck you want to export, then click 'File' -> 'Export'. Choose 'Anki Deck Package (*.apkg)'.
2. **Save File**: Save the `.apkg` file to your computer.
3. **Upload to GitHub**: Create a new repository or use an existing one to upload your `.apkg` file.

This information can be stored in its own README file in your GitHub repository where you'll keep your Anki decks.
