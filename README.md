# Infromation_extraction_using_llms


#This task can be accomplished in a few ways, as listed below.



Using multi-modal models such as LiLT,Donut, LayoutLM, etc., this method needs training data to train these models and has to apply post-processing steps to bring out the expected format.



1. Using AWS textract to extract the tables from the document and applying post-processing techniques to bring out the expected format.


2. using LLM's to get the information out of the documents. Here, we can use two types of llms.

  1. closed-source models or paid services like OpenAI, Claude, and other models.
  2. open source models like Mistral, Zephyr, and others.



In this note book, I have used only llms to extract the information. Here, I have demonstrated in different ways how we can extract the information from the document. first one is using prompt and second one is using schema, schema contain predifined keys need to be extracted from text.But using prompt we can all the information in key value pairs but lot of post processing and prompt optimizing is required.

***Note:*** In this demo, I haven't used any OCR or document loading techniques. This can be done using paddle ocr, AWS textract, gocr, and tesseract. We can easily extract the text from the document. So, I haven't used any approaches here.
