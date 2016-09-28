# Events

##ID
Please use this field to put your name/initials and date on rows you enter data on. In the future this field will be used to create an unique identifier for each person in the Monitor’s database.

##Start Date

##End Date
If an event occurred within a single day - the start and end date should be the same.

Events that occur some point during a range:
> Example:
“On or about August 9, 2006, personnel of the NPF paraded 12 alleged armed robbers—including a 12-year-old—before the media at the Central Police Station in Umuahia, capital of Abia State. They claimed to have arrested the suspects after an exchange of gunfire with the police. Some of those in custody had gunshot wounds, and four others were killed during the incident at Olokobe-Ndume community in Umuahia North Local Government Area of Abia State. Following the parade, the police summarily executed the suspects and deposited their bodies at the premises of the Federal Medical Centre in Umuahia. They claimed that the executed victims signed confessional statements before they were killed. On August 17, 2006, the authorities of the Federal Medical Centre arranged a mass burial for the decomposing bodies of the victims. There were no autopsies or inquests. The police later organized a press conference at which they announced the executions.”

The start date would be 9 August 2006 and the end date would be 17 August 2006. We know the victims were alive as of 9 August and we know they were dead as of 17 August - however when the killing occurred is not clear, it could have happened at any point during that time frame.

If the end date is unclear - there are several ways to determine what should be used:

* Use the date of interview with victim as end date: We can assume that the violation(s) ended at least the month/day of the interview - or that we at least know they occurred up to that date.

>"Abu Bakr, a former detainee in Giwa Barracks told Amnesty International that he had been forced to share a confined area with up to 400 other people [...] Abu Bakr who was held in Giwa barracks told Amnesty International in July 2014: “There was no toilet. To toilet you use a black plastic bag and when you go out you throw it… or if someone used his maybe he will give you.” He also explained: 'We had rice for breakfast. A small amount, they put it in your hand. You give your hand, they will put the rice, you swallow it, you go back to the cell. Later in the day they give you water once. It is in a jug and you drink and pass it to another inside the cell. In the evening it is rice and stew, small. They give it in a nylon bag. There is no washing, no showers. No sleep. You just sit down only, the place is very tight, just sit on your bottom. You can only pray in the cell where you are sitting.'"

So from this the end date would be July 2014 - because we know that at some time in July he talked to Amnesty. 

>“Melvin, a 23-year-old sex worker in Port Harcourt, said she was raped twice by the police. She said: “I was arrested twice. Last month they took all of us to Mile 1 police station. We were six that day, we see different people. They put us in different places [in the police station]. We just have to allow them have sex with us. We were detained for three days. We were asked to pay N3,500 each. The one that will bail you will sleep with you. After that you can go.”

Look at the footnotes - they often will give the date of when the victim was interviewed in this case both footnotes read: “Amnesty International interview in Port Harcourt, October 2011.” - so “last month” would be September 2011 - that would be the start date
While they were detained for three days - it's unclear if it all occurred in September - since Amnesty interviewed this person in October 2011 we’d use that as the end date as they could have been arrested on September 29 and then released on October 1

When the source only mentions a month and no specific date within that month, you can enter that information into the Google sheet by adding an apostrophe in front of the name of the month, e.g. ‘July 2013, which in the field will become July 2013  This way you avoid Google sheets auto-correcting your entry to the first day of given month (in this instance, without the apostrophe, Google sheet would have altered the entry to read: 7/1/2013).

##Location - A specific location of an abuse
>"Stanley Adiele Uwakwe and Faka Tamunotonye Kalio were arrested on 10 May and brought to Old GRA detention centre in Port Harcourt. After several days, they were transferred to another police station, but officers there told relatives that the men were not in detention. Unofficially, relatives were informed that the men had been killed by the police."

While they were detained at Old HRA dentention centre - the location of their killing is unclear. Its also not clear where they were located before they were disappeared - was it at the Old GRA or at the unnamed police station? Since we don’t know we’d leave the Location field blank.
>"And in yet a third case, Human Rights Watch interviewed three witnesses who saw soldiers shoot five men on the Customs Bridge in Maiduguri. One of the victims survived. He told Human Rights Watch that on the afternoon of July 28 soldiers entered a mosque where he was praying with four other men. The soldiers removed their robes, beat them, and marched them to their commander at the bridge. He described what happened next: The soldiers told us to lie down. Four of the soldiers opened fire on us. The commander was watching. I was lying on my side. They saw that some of us were moving and shot us again. I then lost consciousness. I regained consciousness in the night and dragged myself to an area in the dirt near Dandal Community Bank. I spent the night under a bus. In the morning an achaba [commercial motorcycle taxi] man who knew me took me to my house. My family called a doctor…. They removed four bullets from my body. A former Boko Haram member who witnessed the shootings at the Customs Bridge insisted to Human Rights Watch that the five men were not Boko Haram members. According to him, “The old man was holding prayer beads, and Boko Haram members don’t do that. The two youth wore T-shirts and the [other] two men wore long pants, not the short pants of Boko Haram.” The soldiers left the corpses on the bridge for three days."

The location would be “the Customs Bridge” - while Maiduguri would be the City or smallest administrative unit Geoname (more on that below)

A common issue is the separation of specific events contained within a single account of violations based on geography. 

Often a person is arrested and e.g. beaten at a specific site (and the account might include information about other victims being killed at the site of arrest), then transported to another site where they are detained and tortured. Moreover, the conditions during the transportation of detainees/prisoners may amount to violations of fundamental rights and often the narrator describes people dying while being transported. 
In such instances, researchers should consider the initial arrest and transportation to the site of detention to be one event/row and abuses committed or otherwise tied to site of detention a separate even/row. 


##City or smallest administrative unit Geoname
Same reasoning and rules for data entry in this column as applies to the organizations sheet --- please note that often abuse information does not list a city or an LGA if so, leave blank, even if by the description it seems to indicate a particular place. Our job is not to add to abuse reporting, only to transcribe what other groups have reported. Note that often the location mentioned could be either a city or the LGA in which the city is based. In such cases, list the LGA and the associated geoname. 

##City or smallest administrative unit GeonameID

##ADMIN 1 Geoname
Same reasoning and rules for data entry in this column as applies to the organizations sheet --- please note that often abuse reporting is done on a large scale “widespread abuses by police” for instance. Often a researcher will just have to put the country name here as there is no clear indication of a smaller administrative unit than that

##ADMIN 1 GeonameID


##Violation type
The Security Force Monitor uses the HURIDOCs standard

##Description
This is a straight quote from the civil society, governmental or other source about the abusive event. When an event has more than one report tied to it, start the quote with According to X organization “XXX”. According to Y organization “XXX”.

##Perpetrator name
If an individual perpetrator is named in the reporting list it here. Make sure to create a corresponding entry in a Person tab if you have not already.
>"Nwanneka narrated to NOPRIN researchers her experience at the SCID in Enugu in May 2002. She was initially arrested with two other females by officers of the Ninth Mile Police Station on the outskirts of Enugu on charges of assisting an armed robbery suspect, before being transferred to the SCID on May 3, 2002. After taking the statements of the female detainees, NPF Inspector Friday Iyamabo ordered them detained in the cells of the SCID. He later reportedly returned to the cell with pepper spray and powdered chili pepper, ordered the female detainees to strip and one after the other applied the mixture of pepper spray and chili to their genitals after severely beating them with batons. The detainees were denied access to medical treatment. Five years after this experience, Nwanneka reported to NOPRIN researchers in April 2007 that, as a result of this experience, she continues to suffer from complications with both her reproductive system and urinary tract."

##Perpetrator organization
If a specific organization is named in the reporting list it here. Make sure to create a corresponding entry in an Organization tab if you have not already.
>"Amnesty International gathered 15 testimonies, including from five former detainees, on 23 Armoured Brigade confirming the daily deaths of detainees. In the early hours on 2 December 2014, nine soldiers arrested Bashiru Usman (not his real name), a 27-year-old business man, in his house. The soldiers beat him, told him he was a Boko Haram member and took him to their barracks. Several officers interrogated him that morning: “The officer threatened to shoot me for not cooperating. He told me if I cooperate, I will be released, if not, they will shoot me and that is the end of the story. They were slapping me on my head, back, stomach and face. They used a [water] hose to beat me seriously on the back. The interrogation and beating went on for two hours.” Bashiru said that there was not enough space for all detainees to lie down in his cell. Many people in his cell were very sick and died: “Every morning there were two to three dead bodies, likewise in the evenings two people would have died. Not less than five people died per day.” He did not know the exact cause of death but did mention they were only given water once a day and a very small amount of food. He said that at times, the detainees even drank their own urine. After three days Bashiru was released, thanks to the intervention of his lawyer."

##Perpetrator Classification
When the perpetrator is generic “soldiers”, “police” or some other formulation, use this column for a classification from an Organization tab.

>"Shete Obusoh and Chijioke Olemeforo were arrested by police officers from the Special Anti-Robbery Squad on 4 October and spent 17 days in police detention before being taken to court and remanded in prison on 21 October. They said that during this time they were hung from the ceiling in the police station and beaten with gun butts and machetes."

This person was arrested by a specific unit - or type of unit - but then the abuses occurred during their detention at a police station. The Special Anti-Robbery Squad that arrested could have been doing the abuses - but they easily could have not been. So we’d code this as Police - the most generic label - since all we know the is that the abuses occurred while under police detention.

##Source
Source for the entire abuse event. If multiple sources for the same event list them in order of the description, separated by a semicolon.
