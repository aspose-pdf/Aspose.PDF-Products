---
title: Protect and lock PDF document via Java 
weight: 1400
url: /java/protect/pdf/ 
description: Try our On-Premise document APIs to lock PDF file using password on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Encrypt PDF Files via Java" h2="Set document privileges for PDF format with AES-128 encryption." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.PDF" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.PDF " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/pdf/aspose_pdf-for-java.svg" apiHomeLink="https://products.aspose.app/pdf/family" codeSamplesLink="https://github.com/aspose-pdf" liveDemosLink="https://products.aspose.app/pdf/family" docsLink="https://docs.aspose.com/pdf/java/" installationsDocsLink="https://docs.aspose.com/pdf/java/" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/pdf/java" learnAsLink="https://docs.aspose.com/pdf/java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pdf" >}}

{{% blocks/products/pf/agp/content h2="How to Secure PDF File Using Java" %}}

 In order to protect PDF file, we’ll use
 [Aspose.PDF for Java](https://products.aspose.com/pdf/java) 
 API which is a feature-rich, powerful and easy to use encryption API for Java platform. You can download its latest version directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pdf) 
 and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Aspose.PDF" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-pdf</artifactId>
<version>version of aspose-pdf API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Protect PDF Files via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Document protection using Aspose.PDF APIs can be done with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Load PDF with an instance of Document
1.  Use encrypt() method wiht cryptographic algorithm as parameter
1.  Use RC4 40-bit or 128-bit key as well as can use AES 128-bit or 256-bit key as CryptoAlgorithm
1.  Save the secure PDF using save() method

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.PDF for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
-  Get latest version of Aspose.PDF for Java directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-pdf)  .

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="" %}}

```cs

// open PDF File
Document pdfFile = new Document("sourceFile.pdf");
// encrypt PDF
pdfFile.encrypt("user", "owner", 0, CryptoAlgorithm.AESx256);
// save updated PDF
pdfFile.save("EncryptedFile.pdf");

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{% blocks/products/pf/agp/content h2="About Aspose.PDF for Java API" %}}

 Aspose.PDF API can be used for PDF document manipulation and parsing within applications. One can create, modify, compress, secure, print or save PDF to TXT, HTML, PCL, XFA, XML, XPS, EPUB, TEX, Images and more formats. Aspose.PDF is a standalone API and it does not depend on any software including Adobe Acrobat. ‎



{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/about-file-section >}}

    {{< blocks/products/pf/agp/demobox sectionTitle="Free App to Protect PDF" sectionDescription="Check our live demos to [encrypt PDF files](https://products.aspose.app/pdf/protect/pdf) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload PDF file and hit the \"Unlock\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download the resultant PDF file from the link" >}}
    {{< /blocks/products/pf/agp/demobox >}}

    {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. PDF files can be opened in Adobe Acrobat Reader/Writer as well in most modern browsers like Chrome, Safari, Firefox via extensions/plug-ins. Most of the commercially available software suites also offer conversion of their documents to PDF file format without the requirement of any additional software component. Thus, PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, digital signatures, attachments, metadata, Geospatial features and 3D objects in it that can become as part of source document.

    {{< /blocks/products/pf/agp/about-file-text >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Protection Documents" subTitle="Using Java, one can protect other files including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="" name="" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}