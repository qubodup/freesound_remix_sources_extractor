# freesound_remix_sources_extractor
Extract and convert remix sources info from sound edit pages into description-friendly HTML

# How to use

1. Press "Edit sound description" on one of your sounds' pages ([my example](https://freesound.org/people/qubodup/sounds/442827/))

   ![image](https://github.com/user-attachments/assets/65e03327-ae79-446f-883d-9fabbee5d993)
   
2. Right-click "Sound sources" and click on "Inspect"

   ![image](https://github.com/user-attachments/assets/1f44e6bc-f12e-4903-9e3b-b5878788a101)

   In the "Elements" tab, a line starting with `<h5` and containing the text `Sound sources` should be highlighted:

   ![image](https://github.com/user-attachments/assets/fa39dd72-057a-434f-8b73-0057b27192c4)

   If not, restart step 2

3. Right-click the line above "Sound sources" starting with `<div` and click `Copy > Copy element`

   ![image](https://github.com/user-attachments/assets/81cfd986-a3a2-425a-82c8-c799b10c616c)

4. Visit https://qubodup.github.io/freesound_remix_sources_extractor/ and paste (CTRL + V) the copied HTML into the left text area

   ![image](https://github.com/user-attachments/assets/faf50557-138b-4de6-b6f1-6ff38b06f72e)

   You can copy the HTML code on the right to paste it into your Freesound sound description
