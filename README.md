# video_summarizer_ai

--> Installs the transformers library using pip.

-->Imports necessary modules: pipeline from transformers, and YouTubeTranscriptApi from youtube_transcript_api.

-->Sets the youtube_video variable to the YouTube video URL.

-->Extracts the video_id from the YouTube video URL.

-->Imports YouTubeVideo from IPython.display to display the YouTube video in the output.

-->Retrieves the transcript of the YouTube video using the YouTubeTranscriptApi.

-->Creates a summarization pipeline using the pipeline function from transformers.

-->Calculates the number of iterations required to process the result text in chunks of 1000 characters and summarize the text.

-->Converts the summarized_text list to a string representation.
