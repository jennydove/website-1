---
title: "Overview"
date: 2020-04-13T05:31:18Z
draft: false

menu: ["main", "footer"]

menu: 
  main:
    name: Home

---

Right now, digital contact tracing apps are being built around the world to help societies mitigate both the economic and pandemic threats they face. Individual Data Rights for Digital Contact Tracing and Alerting ({{< dcta >}}) are best practices for how consumer {{< dcta >}} systems should respect and handle consumer data. The Data Rights were developed in collaboration with the privacy and security community, human rights and civil liberties organizations, government agencies, technology community, and public health professionals, including epidemiologists. 

## General {{< dcta >}} Data Use

{{< dcta >}} apps can be effective without a consumer having to divulge any personal information to anyone. Data processed within {{< dcta >}} infrastructure may only reveal the following types of information to the following types of individuals:

  * Inform plausibly exposed individuals that they may have been exposed
  * Inform health officials of high level trends in exposure (not individual level)
  * Verifying to authorities that an individual is healthy or sick with the explicit consent of the individual at each verification.

{{< dcta >}} apps should be open source and/or available for audit from an independent third party.

When developing a {{< dcta >}} app, developers should identify one or more well-defined problems in consultation with public health experts that will be mitigated, solved, or improved.

## Individual Data Rights for {{< dcta expand="True">}}

<div class="rights">

  1. Data collection should be limited to achieve a defined purpose and should only collect the minimum data necessary. 
  2. All information disclosed by consumers through a {{< dcta >}} app should be completely opt-in, with clear informed consent both as to the nature of what they're disclosing, how it is used, the likely impacts of disclosure and use, and any choices the consumers may have. Any new use requires fresh consent. Consumers can withdraw their consent at any time.
  3. When consumers choose to altruistically share their health information, that information should remain completely anonymous: no information should be required other than that which is essential, based on epidemiological standards, for alerting others to potential exposure. 
  4. {{< dcta >}} apps must be fully accessible and based on the latest [W3C/WAI standards](https://www.w3.org/WAI/standards-guidelines/mobile/).
  5. Information such as location history, symptom reports, demographic information, or similar shared with public health officials or researchers must never be linked back to or used to re-identify individuals, even by entities legally allowed to perform such linkage. 
  6. Data may be aggregated so that it may not allow for the identification of individuals. Aggregate data should be processed with privacy-protecting techniques such as differential privacy. The methodologies and techniques should be available for public review. Aggregate data may be maintained for public research purposes. Precautions should be taken to ensure that shared aggregate data may not be re-identified downstream.
  7. Application developers should have a very clear and reasonable data retention policy based on epidemiological standards, and must not retain any data for longer than required to achieve the app’s objective. {{< dcta >}} apps should have a clearly defined plan for the destruction of data once {{< dcta >}} apps are no longer necessary.
  8. Data should be secured on the consumer's device according to industry best practices.
  9. Consumers have ownership over the data collected and stored on their mobile devices. 
  10. Data collected-by or derived-from {{< dcta >}} apps should not be monetized, shared, or used for any other non-public-health purpose. This includes third party analytics, ad tracking, and other common third party data collectors. 
  11. {{< dcta >}} apps shall be developed in collaboration with the privacy and security community, human rights and civil liberties organizations, government agencies, technology community, and public health professionals, including epidemiologists.
  12. All {{< dcta >}} apps must be in compliance with local data protection laws and regulations.
  13. {{< dcta >}} apps must not discriminate and developers should perform due diligence to understand the impacts of unintended consequences. 
  14. {{< dcta >}} apps should use an openly published protocol to ensure that their solution is verifiable and interoperable. For example, [the TCN Protocol][4], and [Apple/Google COVID-19 contact tracing technology][5]. 

</div>

 [4]: https://github.com/TCNCoalition/TCN

 [5]: https://www.apple.com/newsroom/2020/04/apple-and-google-partner-on-covid-19-contact-tracing-technology/

## Why are The Data Rights necessary?

Epidemiologists identify {{< dcta >}} as a tool that can help get people treated earlier, and reopen society. For digital contact tracing to be effective, it must have high adoption. However, large scale centralized digital contact tracing could be used for unwanted surveillance. Location-tracking apps have exposed major concerns that these tech solutions will permanently erode the privacy of a large number of the world's population.

It is now apparent that measures needed to control the damage from COVID-19 will be ongoing and long-term. It is crucially important that the tech solutions rapidly built during this period comply with data privacy regulations and do not set the public up for future exploitation. The solution to these problems is requiring that developers build apps on a foundation of privacy-preservation and interoperability. The Data  Rights are necessary to achieve this end.

## What is contact tracing?

Contact tracing is an epidemiological process to help model the spread of an epidemic. It has been used effectively to eradicate smallpox and in the fight against Ebola. It is currently being used as one of the better tools in the fight against COVID-19. 

{{< dcta >}} takes parts of the epidemiological process and applies it to a consumer facing app. Instead of using this process for modeling and other epidemiological uses, the data and processes alert a consumer of a possible infection as early as possible so they can seek advice from health authorities on next steps.

## What is the objective?

The Data Rights should be part of the standard toolkit for developing a {{< dcta >}} app. 

## Who is the audience?

Open source communities, developers and private organizations seem to be leading the charge on creating {{< dcta >}} apps. 

## What happens next? 

Developers: When building apps to aid this pandemic, adopt the {{< dcta >}} Data Rights to build the most effective app without causing harm.

Use them to guide your user stories and UX. The Data Rights have been reviewed and agreed upon by several organizations, however, the Data Rights are a live document. They will likely evolve to address new approaches and standards. Developers are at the frontlines and will need to help contribute to make sure that the Data Rights remain the standard.

## Member organizations

The following organizations have joined to help uphold this data rights framework:


{{< members  >}}
