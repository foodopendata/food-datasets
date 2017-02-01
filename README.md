A list of food dataset-of-allergies provided as a [Simple Data Format Data Package](http://dataprotocols.readthedocs.io/en/latest/simple-data-format.html), compiled at a [School of Data](http://schoolofdata.ch) workshop in preparation for the [Open Food Hackdays](http://food.opendata.ch).

<<<<<<< HEAD
The metadata has been compiled through our web searches, and suggestions from our community.
=======
This dataset was compiled at a [School of Data](http://schoolofdata.ch) workshop in preparation for the [Open Food Hackdays](http://food.opendata.ch).

Currently available in German only.

## Data

This dataset is based on the [Swiss legislation on food allergens](https://www.admin.ch/opc/de/classified-compilation/20050161/201403250000/817.022.21.pdf) (PDF); see p. 37 - *Zutaten, die Allergien oder andere unerwünschte Reaktionen auslösen können*.

## Preparation

Our starting point was the Swiss law, which lists the 14 overarching categories of food ingredients that are the most common allergens, i.e.:

1. Glutenhaltige Getreide
1. Krebstiere
1. Eier
1. Fische
1. Erdnüsse
1. Sojabohnen
1. Milch
1. Hartschalenobst (Nüsse)
1. Sellerie
1. Senf
1. Sesamsamen
1. Schwefeldioxid und Sulfite
1. Lupinen
1. Weichtiere

We created and filled out the data by hand from the PDF. We compared this list to the very similar and more comprehensive one published on [kochenOHNE.de](https://www.kochenohne.de/allergien/liste-der-allergien-intoleranzen/) and even did a manual scrape, but currently are unsure about the [legal terms](https://www.kochenohne.de/allgemeine-geschaeftsbedingungen/) of this website - whether we may republish this list, and what are its sources.

We then looked into the possibility of linking such data to a resource like [FoodAllergy.org](http://www.foodallergy.org/allergens) or the [InformAll database](http://research.bmh.manchester.ac.uk/informAll), which contain detailed information ([example](http://research.bmh.manchester.ac.uk/informall/allergenic-food/?FoodId=5031)) on each allergen. The use of a scientific resource like [AllergenOnline.org](http://www.allergenonline.org/) would be possible with a reliable way to match allergens.

## Notes

We worked on this dataset after looking through the new [OpenFood.ch](http://openfood.ch) online database and API. The various product photos in particular made us realise how time consuming and confusing it may be to try to read through ingredient lists on food packaging. This API does not currently provide structured data on ingredients, but we thought it would be useful to developers to have a master list of allergens to at least be able to do plain text matching. However, we could find no such information resource after a vigorous search (Swiss [Open Data portals](http://opendata.swiss), [Allergy Centre](http://www.aha.ch/swiss-allergy-centre/info-on-allergies/?oid=1444&lang=en), [Health Observatory](http://www.obsan.admin.ch/en/publications), etc.)

It is interesting to compare the legislation on food allergens of different countries. On a superficial level, we saw a few similarities and disparities between [Swiss](https://www.admin.ch/opc/de/classified-compilation/20050161/201403250000/817.022.21.pdf) and [EU laws](http://ec.europa.eu/dgs/health_food-safety/dgs_consultations/food/docs/consult_20150104_allergy-intolerance_guidance.pdf) (PDF; p. 4), each with 14 food groups, and the [U.S. (FDA) guidance](http://www.fda.gov/Food/GuidanceRegulation/GuidanceDocumentsRegulatoryInformation/Allergens/ucm106187.htm) - which focuses on eight major food groups, and includes relevant statistics, such as the medical impact of allergens.

While proprietary resources like the [FoodEssentials API](http://developer.foodessentials.com/API) provide data on allergens for certain (USA only) products, and are used in open source projects like [Lergix](https://github.com/tanysaur/Lergix) and [AllergyAlert](https://github.com/smileypop/AllergyAlert), we are interested in structured data relevant to Switzerland. Furthermore, we believe an effort to create a multilingual (and with alternative spellings) and well-structured open data source would encouragement the development of tools that many people would find beneficial.

Questions:

- What could be considered an "authoritative" source of information?
- Are there any special issues (ethical, medical) to be aware of in using this data?
- Do any efforts exist in academia or industry to create such a common database?
- Would it make sense to crowdsource a potentially much more comprehensive list?
- What would be useful fields and other data sources to link to this one?

See also:

- [E.U. Food information to consumers - legislation](http://ec.europa.eu/food/safety/labelling_nutrition/labelling_legislation_en)
- [U.K. Food Standards Agency - Allergy and intolerance: guidance for businesses](https://www.food.gov.uk/business-industry/allergy-guide)
- [InformAll database of allergenic food materials](http://research.bmh.manchester.ac.uk/informAll)
- [U.S. Food Standards Agency - Resources for allergen information](https://www.food.gov.uk/business-industry/allergy-guide/allergen-resources)
- [FoodAllergens.info](http://www.foodallergens.info/Legal/Labelling/FoodList.html)

Further reading:

- [EUROPREVALL report](http://cordis.europa.eu/publication/rcn/12837_en.html): The prevalence, cost and basis of food allergy across Europe ([summary at EUFIC.org](http://www.eufic.org/article/en/expid/EUFIC_Review_on_Food_Allergens/) - [hier auf Deutsch](http://www.sprechzimmer.ch/sprechzimmer/News/Gesundheit_allgemein/Europaeischer_Allergieverband_EAACI_veroeffentlicht_Erklaerung_zu_Lebensmittelallergien_und_Anaphylaxie.php))
- [Food allergies in developing and emerging economies](https://www.researchgate.net/publication/233962936_Food_allergies_in_developing_and_emerging_economies_Need_for_comprehensive_data_on_prevalence_rates) - Need for comprehensive data on prevalence rates
- [FoodTrade Menu wins Nesta and the ODI’s Food Open Data Challenge](http://www.nesta.org.uk/news/new-service-dishes-data-flag-food-allergens)
- [Open Data Stack Exchange request for allergy data](http://opendata.stackexchange.com/questions/2030/dataset-of-allergies)
- [/r/FoodAllergies/](https://www.reddit.com/r/FoodAllergies/)
>>>>>>> 6687a1bfbf149163375e3fb164ea33828fec359c

## License

This material is licensed by its maintainers under the Public Domain Dedication
and License.

<<<<<<< HEAD
=======
Nevertheless, it should be noted that this material is currently sourced from
several third-parties whose data publishing rights and licensing policies are somewhat
unclear.

>>>>>>> 6687a1bfbf149163375e3fb164ea33828fec359c
If you intended to use these data in a public or commercial product, please
check the data sources themselves for any specific restrictions.
