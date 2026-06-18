# TDM: what does it mean in practice? 

It is difficult to give strict boundaries to the notion of Text and Data Mining. The EU Copyright Directive offers the following definition in its [Article 2](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX%3A32019L0790#d1e845-92-1):

*”‘text and data mining’ means any automated analytical technique aimed at analysing text and data in digital form in order to generate information which includes but is not limited to patterns, trends and correlations”*

Further details are provided in Recital 8:

*“New technologies enable the automated computational analysis of information in digital form, such as text, sounds, images or data, generally known as text and data mining. Text and data mining makes the processing of large amounts of information with a view to gaining new knowledge and discovering new trends possible.”*

In a white paper, the EPC introduces it as  	

*“The ability of new technology to extract meaningful information from vast amounts of data.”*

## TDM vs Artificial Intelligence (AI) and Machine Learning (ML)

Text and data mining techniques are important tools for preparing and analyzing data for use in most AI/ML applications. It is particularly the case for any solution involving large training sets, especially generative AI solutions. 

In March 2023, Thierry Breton, Commissioner for Internal Market of the European Union, gave [useful precisions about the applicability of the TDM exceptions defined in DSM Directive for AI solutions](https://www.europarl.europa.eu/doceo/document/E-9-2023-000479-ASW_EN.html). This answer enforces that for the EU Commission, the use of web content by AI solutions falls into the scope of the Articles 3 and 4 of the DSM Directive. 

## TDM vs search engines

Modern search engines apply TDM/AI/ML techniques to the content they crawl and index. This is reflected by exchanges between experts, for instance in the [IETF AI-Pref forum](https://datatracker.ietf.org/wg/aipref/about/).

It is however highly desirable for providers of Web content to be correctly indexed and ranked by search engines, with limitation on their acceptance to have their content remixed for providing answers without direct reference to the original web page content originates from.

This is why TDMRep expresses a reservation of rights which does not conflict with indexing signals conveyed by robots.txt. 

To be certain that TDM opt-out does not impact the indexation of web content by search engines, we didn't try to extend robots.txt for the sake of defining the TDM reservtion protocol. The technique used in the TDMRep specification for reserving rights relative to web content is very similar to those used in robots.txt, but they do not overlap. For more information about robots.txt, please read [robots for non techies](./robots.html). 

The IETF AI-Pref working group is currently trying to design a vocabulary of content usage, which will allow content providers to clearly signal their preferences regarding the processing of copyrighted content by AI models and systems.  


