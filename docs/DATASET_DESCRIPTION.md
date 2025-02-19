# Database Structure - (Kammal Kilamzia)

The `gatitos.tsv` file follows this structure: ('gatitos.tsv' in anuaia kilamzia zui hi)

| Column Name      | Data Type | Description                                                                 |
|------------------|-----------|-----------------------------------------------------------------------------|
| **word**         | Text      | The Zomi word or phrase.                                                   |
| **meaning**      | Text      | The primary English translation, definition or vocabulary.                 |
| **meaning_1**    | Text      | An alternative or secondary meaning (optional/ Zomi or English).           |
| **example_1**    | Text      | An example sentence using the word in Zomi/ English.                       |
| **example_0**    | Text      | Another example sentence (optional).                                       |
| **pronounce**    | Text      | Link to an audio file or phonetic pronunciation.                           |
| **pending_review**| TRUE     | Indicates if the entry needs review (`TRUE` or `FALSE`).                   |
| **id**           | Number    | A unique identifier for each word (auto-generated).                        |
| **addedby**      | Your Name | The name or ID of the contributor who added the word (optional).           |

Example - (Gehtena)
zomidictionary.tsv
word    meaning    meaning_1    example_1            example_0          pronounce    pending_review    id    addedby
Rest    Tawlnga    Tawlkhawl    "Khang a nei ding hi." "Khang in a um."   khang.mp3    FALSE            1     Lia Cingno
