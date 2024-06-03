![YouTube Subtitles to Instructions Converter](https://github.com/sourceduty/YouTube_Subtitles_Converter/assets/123030236/98a3cbca-351c-4b36-b048-66e7a42189c4)

>  Scrape subtitles from YouTube videos and convert them into detailed step-by-step instructions.

#

This Python GUI program is designed to streamline the process of downloading subtitles from YouTube videos and converting them into detailed step-by-step instructions. Leveraging the tkinter library for the graphical user interface, it provides an intuitive and user-friendly experience. The application consists of several core functionalities, including selecting a file with YouTube links, downloading subtitles from these videos, generating detailed instructions using OpenAI's language model, and displaying progress updates throughout these processes. This makes the tool particularly useful for educators, content creators, and researchers who need to convert video content into instructional text.

One of the standout features of this program is its integration with the youtube-transcript-api, which allows it to fetch subtitles directly from YouTube videos reliably. By replacing the deprecated methods with more robust ones, the program ensures that subtitles are accurately scraped and saved. Users can select a file containing multiple YouTube video links, and the application processes each link to download the corresponding subtitles in both SRT and plain text formats. This automation of subtitle downloading saves users significant time and effort, making it a valuable tool for handling large volumes of video content.

In addition to subtitle downloading, the program utilizes OpenAI's gpt-3.5-turbo model to generate comprehensive instructions from the fetched subtitles. This feature is particularly powerful as it converts the raw subtitle text into coherent and detailed step-by-step instructions, providing users with actionable content derived from video material. By including necessary context, tools, and warnings, the generated instructions are clear and easy to follow. This capability is beneficial for creating instructional materials, summarizing educational videos, or preparing guides based on video content.

The user interface is designed for ease of use, with buttons to load files, download subtitles, create instructions, and clear the displayed text. The progress of each operation is shown in a dedicated progress display area with a black background and white text, ensuring visibility and clarity. This progress display replaces the need for popups, offering a seamless user experience by keeping users informed about the status of their tasks. Overall, this program combines powerful backend functionalities with a straightforward GUI, making it an efficient tool for transforming YouTube video content into detailed instructional text.

***
Copyright (C) 2024, Sourceduty - All Rights Reserved.
