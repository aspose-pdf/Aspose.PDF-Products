---
title: PDF Document Conversion via C++
url: /cpp/conversion/
description: Convert PDF to HTML Image Microsoft Word and many other formats with just few lines of C++ code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PDF File Conversion via C++" h2="PDF to Microsoft Office® Word, HTML, Images and various other formats Conversion" >}}

{{% blocks/products/pf/feature-page-summary %}}
For enhancing the functionality of a C++ software to handle PDF files conversion to other formats. C++ PDF manipulation and rendering library makes it easy for developers. As it supports multiple conversion including PDF to Image, HTML and Microsoft Office Word formats. Programmers can utilize codes listed below as well as enhance as of their relevant requirements.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PDF to Word Formats" %}}
PDF C++ library makes the conversion process simple. So PDF to Word formats conversion including DOC and DOCX files using C++ is just few lines of coding. C++ API provides [Document class](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.document) that load the Microsoft Word<sup>&reg;</sup> files. After loading call the Save method for **PDF to Word conversion**.
{{% blocks/products/pf/feature-page-code h3="C++ PDF to Word Converter Code" %}}

```cs
// Load PDF Source File
auto pdftodoc = MakeObject<Document>(u"sourceInput.pdf");

// Save PDF to Word Document
pdftodoc->Save(u"pdf-to-word.doc", SaveFormat::Doc);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-doc pdf-to-docx" >}}

{{% blocks/products/pf/feature-page-section  h2="Converting PDF to HTML" %}}
Process of converting PDF to HTML in general, is almost same loading the file and call the Save methd having output HTML document path and SaveFormat::Html as parameters. Moreover, for specific HTML saving settings, C++ PDF Parser library provides [HtmlSaveOptions class](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.html_save_options), having different special functionalities like setting for fonts, splitting HTML and CSS in multiple pages, folder for images and more.
{{% blocks/products/pf/feature-page-code h3="PDF to HTML Converter C++ Code" %}}

```cs
// Load the source PDF document
auto pdftoHtmlObj = MakeObject<Document>(u"sourceFile.pdf");

// Create an instance of the HtmlSaveOptions class
SharedPtr<HtmlSaveOptions> pdftoHTMLoptions = MakeObject<HtmlSaveOptions>();

// Set the required options
pdftoHTMLoptions->PartsEmbeddingMode = HtmlSaveOptions::PartsEmbeddingModes::EmbedAllIntoHtml;
pdftoHTMLoptions->LettersPositioningMethod = HtmlSaveOptions::LettersPositioningMethods::UseEmUnitsAndCompensationOfRoundingErrorsInCss;
pdftoHTMLoptions->RasterImagesSavingMode = HtmlSaveOptions::RasterImagesSavingModes::AsEmbeddedPartsOfPngPageBackground;
pdftoHTMLoptions->FontSavingMode = HtmlSaveOptions::FontSavingModes::SaveInAllFormats;

// PDF to HTML Conversion
pdftoHtmlObj->Save(u"pdfto.html", pdftoHTMLoptions);
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Save PDF to Images" %}}
PDF pages to image conversion including TIFF, JPEG, BMP, PNG, etc is easy within C++ based applications using code snippets listed below. Developers can use the [PdfConverter class](https://apireference.aspose.com/pdf/cpp/class/aspose.pdf.facades.pdf_converter#details), Calling the BindPdf for loading the file. Convert the pages via DoConvert then looping through each page and saving as required format image.
{{% blocks/products/pf/feature-page-code h3="C++ PDF to Image Converter Code" %}}

```cs
// instantiate PdfConverter
System::SharedPtr<Aspose::Pdf::Facades::PdfConverter> PdfImageConverter = System::MakeObject<Aspose::Pdf::Facades::PdfConverter>();
// load an existing PDF document
PdfImageConverter->BindPdf(dir + L"sourceFile.pdf");
// convert PDF pages to images
PdfImageConverter->DoConvert();
int32_t imageNumber = 1;
while (PdfImageConverter->HasNextImage()) {
// save each page in JPG format
PdfImageConverter->GetNextImage(dir + imageNumber + L".jpg", System::Drawing::Imaging::ImageFormat::get_Jpeg(), 800, 1000);
imageNumber++;
}
```

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-tiff pdf-to-png pdf-to-jpeg" >}}