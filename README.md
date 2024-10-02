# Video Summarizer
**Overview**

This project, titled "Video Summarizer," focuses on extracting and summarizing information from videos to enhance content accessibility and manageability. The application utilizes OpenAI's Whisper ASR system to convert video audio into text and employs a fine-tuned T5 small model on the CNN/DailyMail dataset to generate summaries. This project addresses the challenges of consuming long video content, particularly for users with time constraints or hearing impairments, by providing concise text summaries.

**Project Structure**

- Audio Extraction and Preprocessing: Converts video to audio using the FFmpeg library. Applies noise reduction techniques to enhance audio clarity.
- Transcription with Whisper: The audio is transcribed into text using the Whisper model, known for its high accuracy across different languages and dialects.
- Text Summarization using T5 Small: The transcribed text is summarized using a fine-tuned T5 small model on the CNN/DailyMail dataset, providing concise and relevant summaries of the original content.
  
**Performance**

- Video Upload: Fast upload processing (~1 second).
- Transcription Display: Whisper takes approximately 9 seconds to transcribe the video content.
- Summary Display: Summaries are generated and displayed within 9 seconds using the fine-tuned T5 small model.
  
**Challenges and Future Improvements**

- Challenges: Dealing with background noise in videos and achieving real-time processing at scale.
- Future Improvements: Optimize the model for multi-language support, closed captioning, and improving summary completeness.
