I. Introduction

Claire initially proposed a project-idea based on hate speech in Eric Zemmour’s campaign, with the following research question-drafts:
What is the volume of hate speech in the public discourse in Eric Zemmour and Eric Zemmour’s supporters?
What kind of hate speech appears?
What is its influence?
Two main academic sources inspired this idea: the first research by Ousidhoum et al. with the title “Multilingual and Multi-Aspect Hate Speech Analysis” sets up a multilingual dataset with several aspects, such as gender, sexual orientation, religion and disability, and analyses how hate speech could be better detected. The second research entitled « La conquête numérique des Identitaires : un effort de mobilisation multi-plateformes » by the Institute for Strategic Dialogue focuses on the hate speech-discourse of the French “Identitaire” far-right political grouping on social media platforms and on their online mobilisation.
After evaluating our capacities and competencies, we decided to slightly change our topic and to move from hate speech-analysis: our second topic proposal was the use of Twitter by French radical right-wing politicians and we wanted to show through a comparative approach how Eric Zemmour and Marine Le Pen use Twitter during the presidential campaign-period.
Finally, we again changed the approach and we decided to include two more politicians, Jean-Luc Mélenchon and Emmanuel Macron, to cover a larger political spectrum. We also chose migration as a case-study topic to restrict our analysis. The reason for this choice is that migration is on the one hand an issue that highly divides politicians and on the one hand it is also very much actual, due to the Ukrainian refugee crisis.
As for the relevance of this final project-idea, we can claim that social media is still (and maybe is more and more) important in politics: it’s a very efficient canal and tool by politicians to address people on a wide scale, an extremely large amount of information can be shared and it is optimal to shape public opinion. Twitter is in this light especially interesting to analyse, since it is a tool that enables politicians to reach a huge mass of voters through very short and pragmatic messages. Migration is, as we mentioned, a currently highly relevant debate topic, also in the context of the presidential campaign. Regarding the timeframe for one of our case studies (1 December 2021-27 March 2022) which covers several months of the campaign-period, it is especially compelling to look at how politicians communicate during these intense times.
We decided to set up three case studies, relating to three research questions:
1) How do French presidential candidates communicate on the topic of migration? (– which doesn’t use a time restriction and so doesn’t explicitly focus on the campaign-period)
2) How important is the topic of migration in the French presidential campaign? (– including now the timeframe)
3) Is the topic of Ukrainian migration treated differently? (- to analyse how the new refugee crisis re-shaped and affected the discourse on migration)
 
II. Other researches and academic background

Regarding our background research, especially what has been already done, we wanted to focus on literature about the use of Twitter by politicians (how social media are involved in politics), how radical right-wing or populist politicians use Twitter (what are their strategies, why Twitter appeals to them), and how Twitter is used in times of elections.
As we could observe, there is already a significant amount of literature and research on these topics. First, regarding the use of Twitter for political discourse or migration as a discourse topic, we selected the following sources:
Alizadeh et al. “Content Moderation As a Political Issue: The Twitter Discourse Around Trump’s Ban”, 16 December 2021, available at : https://fabriziogilardi.org
Agarwal et al. “Hate Speech in Political Discourse: A Case Study of UK MPs on Twitter”. 29 August 2021, available at: https://dl.acm.org.
Walsh, James. “Digital nativism: Twitter, migration discourse and the 2019 election [in Canada]”. 2 August 2021 https://journals.sagepub.com.
Pitropakis et al. “Monitoring Users’ Behavior: Anti-Immigration Speech Detection on Twitter”. 3 August 2020, available at: https://www.mdpi.com.
Datts, Mario. “Social Media, Populism, and Migration”. 8 October 2020, available at: www.cogitatiopress.com. 
Regarding the French specialised researches, we stated that the literature is a bit more restricted, we wanted to highlight especially two sources:
Vanrysselberghe et al. “Sentiment Analysis of French Political Tweets: #MacronPrésident”. 20 January 2019 http://www.thinkmind.org/articles/huso_2019_1_20_88033.pdf 
Buillot et al. “Presidential Election 2012: How French politicians tweet?”. 2 May 2012 https://hal-lirmm.ccsd.cnrs.fr/lirmm-00688651/document 
To shortly summarise all these researches:
The topics appearing are for example
content moderation, focusing on public political discourse on Twitter after the Capitol attack in January 2021
a selection of cross-section of tweets from the 2019 Canadian Federal election, an analysis how migration was framed
 a sentiment analysis on 615 French political tweets relating to Emmanuel Macron
an analysis of opinions expressed through tweets on a specific term within a community, such as a political party, before the 2012 French presidential election
the Twitter conversation between British Members of Parliament and non-MPs, analysing hate speech against MPs
Finally, how is our research different from all these projects? First, we only focus on political tweets by French presidential candidates; second, we only focus on one selected topic (migration); and third, we also use a timeframe during the presidential campaign-period.
 
III. Hypotheses and methodology

We formulated three hypotheses: first, the topics associated with migration keywords would highlight the concerns of each candidate, second, the migration topic will be more important in the political communication of far-right presidential candidates, third, Macron as the current president will often be mentioned, maybe criticised or even attacked for his migration-politics.
To test these hypotheses, we set up three case studies. Our fist case study is focused on the migration topic. We collected data with Minet and built a dataset of 400 tweets for each candidate, scrapping for tweets comprising at least one of our keywords ('étrangers', 'clandestins', 'migrants', 'immigrés', 'réfugiés', 'immigration', 'migration', 'remigration', 'migratoire', 'accueil'). We then cleaned the data by removing the URLs, all punctuation and stopwords. We visualised the data with wordclouds. Last, we performed a topic modelling analysis with a non-negative matrix factorization algorithm to display the topics associated with our keywords and visualised them with termite_plot.
The second case study is focused on the migration topic during the presidential elections. We collected data with Minet and built a dataset made of all tweets published by all major candidates between 01/12/2021 (start of the presidential campaign) and 27/03/2022 (deadline of our project). We visualized the data collected with wordclouds. We then performed a quantitative analysis to find the most viral tweets on the topic of migration. We defined virality as a combination of retweet, likes and replies. We also searched for the number of mentions of other candidates in our corpus to study the way presidential candidates challenge each other on the topic of migration. 
The third case study focuses on the topic of Ukrainian migration. We filtered our previous datasets (our presidential datasets) on the keywords “Ukraine” and “Ukrainian”. We then searched for the most viral tweets of this corpus. 

IV. Analysis of the findings

Case study 1: Migration Datasets 
Our first case study shows that, among the tweets related to migration, “immigration” is the most used word for Mélenchon, Le Pen and Zemmour, but not for Macron, who mostly use “accueil”. “Français” et “étrangers” are also very present in Zemmour’s and Le Pen’s tweets, while “réfugiés” and “France” are quite big on Macron’s and Mélenchon’s wordclouds. 
Our topic modelling analysis illustrates the linkages between the migration topic and other topics made by these politicians. Marine Le Pen links migration with delinquency (topic n° 1), Europe (topic n° 2), military issues (topic n° 3), islam (topic n° 4) and values (topic n°5). Jean-Luc Mélanchon links migration with military issues (topic n° 0 and 3), security issues (topic n° 1), and equality (topic n°4). Emmanuel Macron links migration with security issues (topic n° 2) and European efforts (topic n° 0). Last, Eric Zemmour links migration with security issues (topic n° 3) and French policies that should be changed (topic n° 1 and 2).
Case study 2: Presidential Election Datasets
By building datasets of tweets published by each candidate during the presidential campaign and filtering it with our keywords and by mentions, the following table on the number of tweets could then be built up:
 
 
All tweets
Migration-keywords
Mentioning other candidates within the migration-tweets
Eric Zemmour
2421
258
31
Marine Le Pen
1535
162
8
Jean-Luc Mélenchon
2711
29
5
Emmanuel Macron
372
6
0

Here we see that Mélenchon tweeted the most and Macron definitely the less; Zemmour tweeted the most on migration and he mentioned the most often other candidates, while Macron is very much inactive both regarding migration-tweets and hereby mentioning other candidates (what he actually didn’t do at all).
The wordclouds created with our non-filtered presidential datasets reveal that the national discourse is very important, basically for all four candidates (France, Francais), but maybe the most important for radical right-wing politicians. As for Le Pen, her slogan MarinePrésidente is obviously often used in her tweets. For Macron, the Ukrainian refugee crisis seems to be the core topic in his tweets; and Mélenchon also transmits quite positive, welcoming tweets on the Ukrainian crisis (accueillir des gens, etc.).
We then assessed the virality of each candidate’s migration related tweets during the presidential campaign, and obtained these results: 
 
 
By likes
By retweets
By replies
Eric Zemmour
Zemmour: “For 5 years, Emmanuel Macron has carefully refused to "fuck with" the scum, the gangs, the apprentice jihadists, the outlaw immigrants, the antifas and the ideologues who brainwash our children. Cowardly to the strong, cruel to the weak.”
5 January 2022, 24369 likes 
Zemmour: “For 5 years, Emmanuel Macron has carefully refused to "fuck with" the scum, the gangs, the apprentice jihadists, the outlaw immigrants, the antifas and the ideologues who brainwash our children. Cowardly to the strong, cruel to the weak.”
5 January 2022, 7886 retweets
Zemmour: “In Alsace, the French welcome me as a friend. In Barbès, the Algerians boo me like an enemy. Everything is said.” 
18 December 2021, 1230 replies
Marine Le Pen
Le Pen: “The behaviour of these supporters of Algeria says everything about the failure of
50 years of lax migration. It is time for the automatic acquisition of nationality to be abolished.” 
19 December 2021, 3404 likes
Le Pen: “I support Inger Støjberg, former Danish minister, sentenced to two months in prison for defending underage girls forced into early and forced marriages. Our Europe is losing its mind!” 
13 December 2021, 1243 retweets
Le Pen: “The behaviour of these supporters of Algeria says everything about the failure of
50 years of lax migration. It is time for the automatic acquisition of nationality to be abolished.” 
19 December 2021, 952 replies
Jean-Luc Mélenchon
Mélenchon: “The macronie in action. Policemen stashed away, military bogged down, the morgue ridiculed, the refugees rescuing all these suckers.” [reaction to a French vigipirate vehicle stuck in the mud] 
19 December 2021, 2655 likes
Mélenchon: “The macronie in action. Policemen stashed away, military bogged down, the morgue ridiculed, the refugees rescuing all these suckers.” [reaction to a French vigipirate vehicle stuck in the mud] 
19 December 2021, 835 retweets
Mélenchon: “The macronie in action. Policemen stashed away, military bogged down, the morgue ridiculed, the refugees rescuing all these suckers.” [reaction to a French vigipirate vehicle stuck in the mud] 
19 December 2021, 638 replies
Emmanuel Macron
Macron: “Hundreds of thousands of Ukrainian refugees are fleeing the country. They are and will be welcomed in our Union. France will do its part. To our cities, our villages, our associations that are mobilising: thank you.” 
2 March 2022, 5982 likes
Macron: “Hundreds of thousands of Ukrainian refugees are fleeing the country. They are and will be welcomed in our Union. France will do its part. To our cities, our villages, our associations that are mobilising: thank you.” 
2 March 2022, 825 retweets
Macron: “Our external borders are shared, our common area of free movement must be preserved: it is therefore as Europeans that we must build a response to the challenges of asylum and migration, with efficiency and solidarity.” 
2 February 2022, 709 replies


We can see that Zemmour reacts the most to other candidates, especially to Macron, while Le Pen, the other radical right-wing candidate also reacts to Macron the most – from the tweets, it is clear that both are actively criticising Macron for his migration-politics. It is also interesting how Zemmour and Le Pen try to distance themselves from the other candidate, as both come from the same political spectrum, and they are actually also criticising each other, though not to the degree than criticising Macron. On the contrary, Mélenchon doesn’t criticize explicitly Macron but rather the two radical right-wing candidates.
Case study 3: Ukrainian migrants (Anna)
This small excursion attempted to highlight how the Ukrainian refugee crisis might has shaped the migration-related discourse of all candidates. We simply added some more keywords to the second dataset (‘Ukraine’, ‘ukrainien’, ‘l’Ukraine’) and then looked at which tweets achieved the most likes and retweets.



Most viral tweet on Ukraine
Eric Zemmour
Zemmour: “I want to temporarily welcome the Ukrainian refugees who are our European and Christian brothers. I do not want African immigrants to take advantage of this, as is already the case. #Elysee2022 #ZemmourVsMacron” 
17 March 2022, 3740 likes, 1186 retweets
Marine Le Pen
Le Pen: “Ukraine is a European country, it is natural that European countries welcome European refugees. #MarinePrésidente #FacingBFM” 
1 March 2022, 1763 likes, 362 retweets
Jean-Luc Mélanchon
Mélenchon: "We stand with the refugees from Ukraine, who now number over one million. We stand with all Ukrainians who are suffering the horror of war and resisting. We stand with all Russians who are standing up against Vladimir Putin.” 
6 March 2022, 965 likes, 376 retweets
Emmanuel Macron
Macron: “Hundreds of thousands of Ukrainian refugees are fleeing the country. They are and will be welcomed in our Union. France will do its part. To our cities, our villages, our associations that are mobilising: thank you.” 
2 March 2022, 5982 likes, 825 retweets


It is clear that suddenly all the four candidates show very positive messages, solidarity and help. It is especially interesting how Zemmour and Le Pen changed their discourse and emphasise how Ukrainian refugees differ from other (“African”) refugees, since they come from Europe and are Christians, which justifies their welcoming in France. We can also see that in this topic, Macron achieves the most likes, which might also support the fact that his popularity as a president has grown during the Ukrainian war.

V. Conclusion and summary of findings

To conclude, there appears to be a linkage between insecurity and migration for Marine Le Pen and Eric Zemmour, between migration and war for Jean-Luc Mélenchon, and between migration and Europe for Emmanuel Macron. 
Our second case study shows that Marine Le Pen’s and Eric Zemmour’s most viral tweets on migration appear to criticise migrants ; Jean-Luc Mélenchon’s most viral tweets on migration praise migrants ; Emmanuel Macron’s most viral tweets on migrants address the Ukrainian crisis. Eric Zemmour and Marine Le Pen harshly criticise Macron’s migration-politics; Jean-Luc Mélenchon criticises right-wing politicians; Emmanuel Macron doesn’t react to other candidates.
Our third case study shows a clear change of narrative of all candidates regarding migration when it comes to Ukrainian migrants.

