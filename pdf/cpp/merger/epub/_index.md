---
title: Merge EPUB Files via C++
weight: 120
url: /cpp/merger/epub/
description: C++ example code to combine EPUB documents on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Merge EPUB Files using C++" h2="EPUB document merger using server-side C++ APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="" pfName="Aspose.PDF" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="EPUB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/cpp" installationsDocsLink="https://docs.aspose.com/pdf/cpp" nugetLink="https://www.nuget.org/packages/aspose.pdf" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/cpp" learnAsLink="https://docs.aspose.com/pdf/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Merge EPUB File Using C++" %}}

 In order to merge EPUB file, we’ll use
 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp)
 API which is a feature-rich, powerful and easy to use document merger API for C++ platform. You can download its latest version directly, just open
 [NuGet](https://www.nuget.org/packages/aspose.pdf)
 package manager, search for
 **Aspose.PDF.Cpp**
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```powershell

PM> Install-Package Aspose.PDF.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps for Merging EPUB Files in C++" %}}

{{% blocks/products/pf/agp/text %}}

 A basic document merging and concatenating with
 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp)
 APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

+  Load both EPUB files.
+  Use get\_Pages() method to get document pages.
+  Use Add() function to merge.
+  Use save() method to save at specified path

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.PDF for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
- Aspose.PDF for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Merge EPUB Files - C++" offSpacer="" %}}

```cpp
// Open first document
auto doc1 = MakeObject<Document>(u"file1.epub");

// Open second document
auto doc2 = MakeObject<Document>(u"file2.epub");

// Add pages of second document to the first
doc1->get_Pages()->Add(doc2->get_Pages());

// Save concatenated output file
doc1->Save(u"merged-output.epub");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}


<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.PDF for C++ API" %}}

 Aspose.PDF API can be used for PDF document manipulation and parsing within applications. One can create, modify, compress, secure, print or save PDF to TXT, HTML, PCL, XFA, XML, XPS, EPUB, TEX, Images and more formats. Aspose.PDF is a standalone API and it does not depend on any software including Adobe Acrobat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Online EPUB Merger Live Demos" sectionDescription="Merge EPUB documents right now by visiting our [Live Demos website](https://products.aspose.app/pdf/merger). The live demo has the following benefits" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Just upload your EPUB files." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" It will be merged and concatenated instantly." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EPUB" readMoreLink="https://docs.fileformat.com/ebook/epub/" >}}
Files with .EPUB extension are an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. For example, on Mac OS, the pre-installed Books software provides the support for opening such files. In addition, there are a lot of compatible software available for smartphones, tablets and computers. EPUB file standards are maintained by the International Digital Publishing Forum (IDPF). The version EPUB 3 is also endorsed by the Book Industry Study Group (BISG), a leading book trade association for standardized best practices, research, information and events, for packaging of content.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Merging Formats" subTitle="Using C++, One can also merge many other file formats including.." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/cgm/" name="CGM" description="Computer Graphics Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/html/" name="HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/md/" name="MD" description="Markdown Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/pcl/" name="PCL" description="Printer Command Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/svg/" name="SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/tex/" name="TEX" description="LaTeX Output Text" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/xml/" name="XML" description="Extensible Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/xps/" name="XPS" description="XML Paper Specifications" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/pdf/cpp/merger/xslfo/" name="XSLFO" description="XSL Formatting Objects" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}