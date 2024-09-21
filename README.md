# Spam Filter Project

![0_SHZ7ehjxCaS7-VBp](https://github.com/user-attachments/assets/5d94b9a9-a137-4ec9-9850-1978a5558edf)


This project implements a spam filter using machine learning techniques.
The model is trained on a dataset of SMS messages and classifies them as either "ham" (not spam) or "spam".

#The goal of this project is to build a spam detection system that can accurately classify SMS messages as spam or not. The project utilizes Natural Language Processing (NLP) techniques and machine learning algorithms.


### Dataset Details

- **Number of Samples**: 5,572 messages
- **Features**:
  - **v1**: Indicates whether the message is "ham" or "spam".
  - **v2**: The actual text of the SMS message.
  
| v1   | v2                                              |
|------|-------------------------------------------------|
| ham  | Go until jurong point, crazy.. Available only... |
| spam | Free entry in 2 a wkly comp to win FA Cup...    |
| ham  | Nah I don't think he goes to usf, he lives around... |

### Data Preprocessing

Before training the model, the following preprocessing steps were applied:
- Removed unnecessary columns.
- Cleaned the text data by:
  - Lowercasing the text.
  - Removing punctuation and special characters.
  - Tokenization and stemming.
  - Eliminating stop words.

