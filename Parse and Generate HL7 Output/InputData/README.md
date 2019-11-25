## How to parse and generate hl7 output for input data in C# and ByteScout Document Parser SDK

### How to parse and generate hl7 output in C# with easy ByteScout code samples to make input data. Step-by-step tutorial

These simple tutorials explain the code material for beginners and advanced programmers who are using C#. ByteScout Document Parser SDK was designed to assist input data in C#. ByteScout Document Parser SDK is the customizable data extraction platform for batch data extraction from documents. Relies on special templates that can be created with no special technical skills required. Supports millions of documents as input and designed to handle multiple threads. Can output data as JSON, CSV, XML or custom format.

C# code snippet like this for ByteScout Document Parser SDK works best when you need to quickly implement input data in your C# application. For implementation of this functionality, please copy and paste the code below into your app using code editor. Then compile and run your app. Use of ByteScout Document Parser SDK in C# is also described in the documentation given along with the product.

Trial version of ByteScout is available for free download from our website. This and other source code samples for C# and other programming languages are available.

## REQUEST FREE TECH SUPPORT

[Click here to get in touch](https://bytescout.zendesk.com/hc/en-us/requests/new?subject=ByteScout%20Document%20Parser%20SDK%20Question)

or just send email to [support@bytescout.com](mailto:support@bytescout.com?subject=ByteScout%20Document%20Parser%20SDK%20Question) 

## ON-PREMISE OFFLINE SDK 

[Get Your 60 Day Free Trial](https://bytescout.com/download/web-installer?utm_source=github-readme)
[Explore SDK Docs](https://bytescout.com/documentation/index.html?utm_source=github-readme)
[Sign Up For Online Training](https://academy.bytescout.com/)


## ON-DEMAND REST WEB API

[Get your API key](https://pdf.co/documentation/api?utm_source=github-readme)
[Explore Web API Documentation](https://pdf.co/documentation/api?utm_source=github-readme)
[Explore Web API Samples](https://github.com/bytescout/ByteScout-SDK-SourceCode/tree/master/PDF.co%20Web%20API)

## VIDEO REVIEW

[https://www.youtube.com/watch?v=MG5FfTWWSVE](https://www.youtube.com/watch?v=MG5FfTWWSVE)




<!-- code block begin -->

##### **TestReportFormat.yml:**
    
```
templateVersion: 3
templatePriority: 0
sourceId: Untitled document kind
detectionRules:
  keywords: []
fields:
  LabName:
    type: rectangle
    rectangle:
    - 98.4065933
    - 33.2967033
    - 90
    - 8.24175835
    pageIndex: 0
  LabAddress:
    type: rectangle
    rectangle:
    - 99.0659332
    - 42.3626366
    - 89.175827
    - 9.23077011
    pageIndex: 0
  LabCity:
    type: rectangle
    rectangle:
    - 100.549454
    - 53.0769272
    - 21.7582436
    - 8.90109921
    pageIndex: 0
  LabState:
    type: rectangle
    rectangle:
    - 125.109894
    - 52.9120865
    - 12.5274725
    - 8.24175835
    pageIndex: 0
  LabZip:
    type: rectangle
    rectangle:
    - 138.131882
    - 52.5824203
    - 24.3956051
    - 8.90109921
    pageIndex: 0
  LabPhone:
    type: rectangle
    rectangle:
    - 115.219788
    - 63.4615402
    - 51.7582436
    - 7.74725294
    pageIndex: 0
  LabFax:
    type: rectangle
    rectangle:
    - 184.780212
    - 63.9560471
    - 52.5824203
    - 7.91208792
    pageIndex: 0
  PatientLastName:
    type: rectangle
    rectangle:
    - 18.6075935
    - 106.139236
    - 21.8354435
    - 9.49367046
    pageIndex: 0
  PatientFirstName:
    type: rectangle
    rectangle:
    - 150.759491
    - 106.329109
    - 37.0253143
    - 8.54430389
    pageIndex: 0
  PatientSSN:
    type: rectangle
    rectangle:
    - 18.6075935
    - 125.316452
    - 99.4936676
    - 9.68354416
    pageIndex: 0
  PatientAge:
    type: rectangle
    rectangle:
    - 150.949371
    - 125.126579
    - 35.3164558
    - 10.2531643
    pageIndex: 0
  PatientDOB:
    type: rectangle
    dataType: date
    rectangle:
    - 190.5
    - 125.25
    - 38.25
    - 9.75
    pageIndex: 0
  PatientAddress:
    type: rectangle
    rectangle:
    - 18.7974682
    - 144.493668
    - 189.113922
    - 9.8734169
    pageIndex: 0
  PatientHomePhone:
    type: rectangle
    rectangle:
    - 18.3870964
    - 163.548386
    - 90.9677429
    - 11.1290321
    pageIndex: 0
  PatientWorkPhone:
    type: rectangle
    rectangle:
    - 114.677414
    - 164.032242
    - 71.6128998
    - 11.1290321
    pageIndex: 0
  PatientChartNo:
    type: rectangle
    rectangle:
    - 209.516129
    - 164.032242
    - 91.9354858
    - 11.1290321
    pageIndex: 0
  PhysicianName:
    type: rectangle
    rectangle:
    - 305.806427
    - 104.999992
    - 259.838715
    - 10.6451607
    pageIndex: 0
  PhysicianAccountName:
    type: rectangle
    rectangle:
    - 305.806427
    - 125.80645
    - 165.967743
    - 9.1935482
    pageIndex: 0
  PhysicianAccountNo:
    type: rectangle
    rectangle:
    - 480
    - 125.322578
    - 92.9032211
    - 10.1612902
    pageIndex: 0
  PhysicianNPI:
    type: rectangle
    rectangle:
    - 308.035736
    - 163.392853
    - 94.2857132
    - 11.7857141
    pageIndex: 0
  PhysicianPhone:
    type: rectangle
    rectangle:
    - 409.821442
    - 163.928589
    - 79.821434
    - 9.64285755
    pageIndex: 0
  PhysicianFax:
    type: rectangle
    rectangle:
    - 494.516113
    - 164.032242
    - 77.4193497
    - 11.1290321
    pageIndex: 0
  InsuranceName:
    type: rectangle
    rectangle:
    - 17.9032249
    - 263.2258
    - 279.677399
    - 8.70967674
    pageIndex: 0
  InsurancePolicy:
    type: rectangle
    rectangle:
    - 16.9354839
    - 302.903229
    - 57.5806465
    - 9.67741871
    pageIndex: 0
  InsuranceGroup:
    type: rectangle
    rectangle:
    - 151.935471
    - 302.903229
    - 62.4193573
    - 9.67741871
    pageIndex: 0
  InsuredName:
    type: rectangle
    rectangle:
    - 18.3870964
    - 322.741943
    - 77.9032211
    - 12.0967741
    pageIndex: 0
  InsuredSSN:
    type: rectangle
    rectangle:
    - 149.032257
    - 323.709686
    - 89.5161285
    - 10.1612902
    pageIndex: 0
  InsuredDOB:
    type: rectangle
    dataType: date
    rectangle:
    - 244.5
    - 322.5
    - 54.75
    - 10.5
    pageIndex: 0
  CollectionDate:
    type: rectangle
    rectangle:
    - 86.756752
    - 351.891876
    - 55.9459457
    - 9.32432365
    pageIndex: 0
  CollectionTime:
    type: rectangle
    rectangle:
    - 263.035736
    - 352.5
    - 29.4642868
    - 8.57142925
    pageIndex: 0
  PatientGenderMale:
    type: rectangle
    rectangle:
    - 273.214294
    - 128.035721
    - 8.0357151
    - 6.96428585
    pageIndex: 0
  PatientGenderFemale:
    type: rectangle
    rectangle:
    - 289.285736
    - 127.5
    - 7.50000048
    - 8.0357151
    pageIndex: 0
  PhysicianAddress:
    type: rectangle
    rectangle:
    - 305.892883
    - 145.714294
    - 176.785721
    - 8.0357151
    pageIndex: 0
  BillToIsPhysician:
    type: rectangle
    rectangle:
    - 53.035717
    - 206.250015
    - 8.57142925
    - 6.96428585
    pageIndex: 0
  BillToIsMedicare:
    type: rectangle
    rectangle:
    - 95.8928604
    - 206.250015
    - 8.0357151
    - 7.50000048
    pageIndex: 0
  BillToIsMedicaid:
    type: rectangle
    rectangle:
    - 139.285721
    - 206.250015
    - 8.0357151
    - 8.0357151
    pageIndex: 0
  BillToIsInsurance:
    type: rectangle
    rectangle:
    - 183.750015
    - 206.250015
    - 7.50000048
    - 7.50000048
    pageIndex: 0
  BillToIsPatient:
    type: rectangle
    rectangle:
    - 231.428589
    - 206.250015
    - 7.50000048
    - 6.4285717
    pageIndex: 0
  RelationToPatientIsSelf:
    type: rectangle
    rectangle:
    - 117.321434
    - 245.357147
    - 7.50000048
    - 8.0357151
    pageIndex: 0
  RelationToPatientIsSpouse:
    type: rectangle
    rectangle:
    - 144.642868
    - 244.821442
    - 8.0357151
    - 8.57142925
    pageIndex: 0
  RelationToPatientIsDependent:
    type: rectangle
    rectangle:
    - 184.821442
    - 245.357147
    - 6.96428585
    - 7.50000048
    pageIndex: 0
  CollectionTimeIsAM:
    type: rectangle
    rectangle:
    - 303.75
    - 354.107178
    - 6.96428585
    - 6.4285717
    pageIndex: 0
  CollectionTimeIsPM:
    type: rectangle
    rectangle:
    - 328.392883
    - 354.642853
    - 7.50000048
    - 7.50000048
    pageIndex: 0
  ICD10DxCodes:
    type: rectangle
    rectangle:
    - 17.6785736
    - 381.964325
    - 73.9285736
    - 10.7142868
    pageIndex: 0
  ClinicalHistoryIsRoutinePap:
    type: rectangle
    rectangle:
    - 18.7500019
    - 423.214294
    - 7.50000048
    - 8.0357151
    pageIndex: 0
  ClinicalHistoryIsAbnormalBleeding:
    type: rectangle
    rectangle:
    - 20.3571453
    - 433.392853
    - 6.96428585
    - 9.1071434
    pageIndex: 0


```

<!-- code block end -->