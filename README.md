# Project Title

DSC160 Data Science and the Arts - Midterm Project Repository - Spring 2020

Project Team Members: 
- Brian Qian, brqian@ucsd.edu
- Emma Logomasini, elogomas@ucsd.edu
- Nicholas Kho, nikho@ucsd.edu

## Abstract

The Korean music industry is often seen as a bright and fresh representation of East-Asian creativity that has captured the world’s attention. In this project, we will be taking a look at numerous decades of popular music in Korea from the 1910s to the 2010s to understand the connection between distinctive musical styles and major political events that coincide with them. Part of what makes this possible analysis intriguing is that Korea has been under the cultural influence of two major powers in the last century in addition to dealing with oppressive regimes. Our goal is to try to measure the influence of these events in the difference of genres.

Our research question is: do we see similar features in time periods that dealt with similar historical issues, in this case, political repression or economic growth? Our hypothesis is that we will see similarities in periods of great political conflict. To further cognize the influence of political changes, we will be extracting information in forms of features such as MFCCs, temporal, and spectral statistics on a dataset of representative music of each major political era in recent Korean history. Thus we will be able to further attribute certain characteristics towards the political and cultural events, whether positive or negative, that occured within the same timeframe. 

As for the technical process, we will be utilizing jupyterhub and numerous libraries such as Seaborn, matplotlib, and LibROSA to extract and display the features we will be taking into consideration. Our results will be formatted among graphs and charts to give a visual perception of each distinct era of political change. We feel like we can make a “timeline” to represent the different features of each area, and this project will give us further insight into the history of Korean music which has become a global genre in today’s world. Overall, we want to see if there is a correlation between the characteristics of popular Korean music and major political events throughout time, and whether or not the relationship is substantial. 

In terms of dataset, we will be utilizing suggested important songs of each era as outlined in the Sogang University's Professor Huikyong Pang’s class “The Mediums of Korean Cultural Modernity.” In addition, we took a look at Melon [Korean’s music chart ranking since 2004] chart data for recent popular singles to highlight major songs that have impacted the recent decades. As for the major political and cultural events during each era we will be using a [South Korean timeline](https://www.bbc.com/news/world-asia-pacific-15292674) created by BBC.


## Data

From 1910-1945, Korea was under Japanese Colonization where the emergence of mass media, newspapers and Japanese TROT music, notable for its common sad themes, was introduced in the 1920s. By the 1930s the recording industry in Korea began to fully develop with the introduction of the phonograph. During this time, Japan often censored recordings that they deemed "troublesome." The songs we found the most prominent during this era were the following:

    1. "희망가" Huimangga (1925)
    "Huimangga" was a popular Changga (Anti-Japanese) song that was sung to express the people's hope of regaining the country's sovereignty. While the song doesn't have a specific recording or artist, it was one of the earliest pop record that was inspired by Western and Christian hymns
    https://www.youtube.com/watch?v=F-HwLfgi_5o

    2. "Glorification of Death" by Yun Sim-deok (1926)
    https://www.youtube.com/watch?v=lsxwHLGG_v4&list=LLqp5LSKwhs3T11Fu_neLoBA&index=96
    (not the original recording)

    3. “Tears of Mokpo” by Lee Nan-yeong (1935)
    "Tears of Mokpo" is based off the city, Mokpo, in Korea which became symbolic of Japan's victory and control of Korea.
    https://www.youtube.com/watch?v=kNCQjn2GX7M

    4. “My Brother is a Street Musician” (오빠는 풍각쟁이야) by Park Hyang-rim (1938)
    https://www.youtube.com/watch?v=tev48pcM8ws

From the 1940s to the 1950s, after the United States liberated Korea from Japanese control (1945), the Korean War (1950-1953) occurred between North Korea and South Korea. During this time Korea was under the right-wing government led by Syngman Rhee (1948-1960), who became known for killing and arresting leftist opponents, political oppression, and taking away term limits for officials. In 1956 the first television station was broadcasted, and in general the 50s brought Korea mass urbanization, a booming popular culture, and Americanization through performers, salons, clubs, and military radio.

    5. "Go Away 38th Parallel" by Nam In Soo (1949)
    https://www.youtube.com/watch?v=jqkh26uaMAU 

    6. "Guitar Boogie" by Yoon Ilro (1950)
    The song was a popular iteration of the corresponding Western song that provided dance music to Korea.
    https://www.youtube.com/watch?v=4ADWBa9z2Rs

    7. "Farewell in Busan Station" (1953)
    https://www.youtube.com/watch?v=tm4HJXZShww
    (not the original recording)

    8. "Be strong! Keumsun!" (1953)
    https://www.youtube.com/watch?v=DpJGl7FYI58

In the 1960s, the April Revolution began with mass protests against the President Syngman Rhee, eventually leading to his resignation. The same year, South Korea held a democratic election where Yun Bo-soen was elected, but by May 16, 1961 Park Chung-hee began a coup d’etat where he gained the presidency in 1962. In 1961, Korea's 1st government tv broadcasting station, KBS, was created, and Park Chung-hee utilized it to promote anti-communism and Americanization. The 60s in South Korea saw a better economy, more televisions, and American music played on TV. 

    9. “Camelia Lady” by Lee Mi-ja (1964)
    A popular Trot song amogst populace.
    https://www.youtube.com/watch?v=y8ChOe12BLs
    
    10. "A Cup of Coffee" by Pearl Sisters (1968)
    American inspired soul song popular among upper/middle class.
    https://www.youtube.com/watch?v=4r66aMnWWCM
    
    11. "My Beloved Is Far Away; Before Being Late" by Kim Choo-ja (1969)
    https://www.youtube.com/watch?v=WlY29K1k3z0
    
In the 1970s, the Yushin Regime was founded as the Fourth Republic of Korea legally allowing Park Chunghee to hold a dictatorship. During this time, there was a curfew that was set and women could get arrested for short skirts among many other laws that were issued. This further caused tension between older generations who valued tradition and the younger generations that were social intellectuals influenced by American values. By the end of the decade in 1979, dictator Park Chunghee was assassinated by the Korean CIA, and the month following, a new coup-de-tat was formed making Cheon Doo-Hwan the new dictator. 

    12. "To The Happy World" by Han dae soo (1974)
    Han dae soo was a popular folk muscian heavily inspired by American youth values, who created music with themes of wanting freedom.
    https://www.youtube.com/watch?v=H1cG8BB4fts
    
    13. "Give me water" by by Han dae soo (1974)
    https://www.youtube.com/watch?v=m3z0HJirgQI
    
During the 1980s, the Gwangju Democracy Movement started at the beginning of the decade with massive protests leading to many protesters being killed by the government. The government further blamed the communist party for the protests. By 1987, Roh Tae-woo was announced as the 6th president which led to more major protests, and finally the presidential elections were reinstated. A new "3S" policy was passed to distract the general population from politics with sports, sex, and screen. Under this time, the media was under state control and the teenage demographic became a consumer group.

    14. "좋아해" by Na Mi (1980)
    https://www.youtube.com/watch?v=8cEvJSY05GQ
    
    15. "Short Hair" by Cho Yong-Pil (1980)
    "Short Hair" was a popular pop ballad song during the 80s.
    https://www.youtube.com/watch?v=c7ZVo6SBQ9Q
    
    16. "그 사람 미워요" by Kim Wan Sun (1986)
    Kim Wan Sun was known as Korea's Madonna
    https://www.youtube.com/watch?v=qqeusNyLtws
    
    17. "Last night" by SoBangCha (1988)
    SoBangCha was a popular dance trio of Na Mi, Kim Wan Sun, and Park Nam Jung who were all major dance artists that were popular among teens.
    https://www.youtube.com/watch?v=ErewtVOZn6M
    
    18. 'Missing you' by Park Nam Jung (1989)
    https://www.youtube.com/watch?v=g21lBGfnzfs

The 1990s in South Korea saw the introduction of Neoliberalism which made things more competitive especially for students. The idea of culture also saw a shift into being a commodity, and record labels began shifting into a J-pop inspired model that includes inhouse training, recording, and managing. Labels further focused more on an all-round entertainer over just a musician. In 1995 the major record label, SM entertainment was founded. However by 1997 South Korea faced an economic collapse which devasted the independent music industry. By the end of the decade, the new South Korean president, Kim Dae-jung, issued the "Sunshine Policy" which offered humanitarian aid to North Korea

    19. "COME BACK HOME" by "Seotaiji and Boys" (1995)
    The song was heavily influenced by "gangsta" rap that originated in America.
    https://www.youtube.com/watch?v=q3xy4p2JTfU
    
    20. "Candy" by H.O.T (1996)
    H.O.T was considered to be the first major K-pop idol group following the change in the music industry, and their successful model was implemented for the many K-pop groups that came after them.
    https://www.youtube.com/watch?v=GMsc7wGghy8
    
    21. "Im Your Girl" by S.E.S (1997)
    https://www.youtube.com/watch?v=WpmTLDtr4qY

In the 2000s, Kim Jong-il of North Korea and the South Korean president, Kim Dae-jung held a submit which lead to a mutual agreement among both leaders. In August of 2000, the Border offices reopen and for the first time North Koreans and South Koreans were allowed to meet. The Korean music market expansion also slowed down, and thus the industry started to go into new asian markets like China. It became so popular that it was called "Hallyu" (Korean Wave) that lead to the extraordinary growth of Korean culture from music to television all around the world. In 2002, the kdrama, Winer Sonata, became a major phenomenon among other Asian countries. While Trot music and Ballads were still very popular at this time, the Kpop groups took over the industry. By the end of the decade, North Korea and South Korea scrapped all military and political deals leading to multiple naval battles. 


    22. "Eat You Up" by BOA (2008)
    https://www.youtube.com/watch?v=OLnr2u_nj10
    
    23. "LA LA LA" by SE7EN (2008)
    https://www.youtube.com/watch?v=arUScZVMtgc
    
    24. "Rainism" by Rain (2008)
    https://www.youtube.com/watch?v=QDYax6ABb-8
    
    25. "Mirotic" by TVXQ (2008)
    https://www.youtube.com/watch?v=HtJS32n6LNQ

In the 2010s, the tension between North and South Korea grew with multiple conflicts including exchange of fire across land and sea borders from 2010 to 2014. In 2014, the Sewol ferry incident led to over 200 deaths of South Koreans high schoolers due the captain and crew's misdoings. In 2016, the THAAD missile system was deployed in South Korea which led to the ban of Korean media in China. The following year, President Park Geun-hye was impeached and imprisoned after she allowed a personal friend with a lack of government position to interfere in affairs of state. By the end of the decade after numerous incidents throughout the past few years, North Korea and South Korea agreed to end all hostile actions against each other, and marched under the same flag during South Korea's 2018 Winter Olympics.

    26. "Monster" by EXO (2016)
    https://www.youtube.com/watch?v=KSH-FVVtTf0
    
    27. "TT" by Twice (2016)
    https://www.youtube.com/watch?v=ePpPVE-GGJw
    
    28. "Don't Wanna Cry" by SEVENTEEN (2017)
    https://www.youtube.com/watch?v=zEkg4GBQumc
    
    29. "DNA" by BTS (2017)
    https://www.youtube.com/watch?v=MBdVXkSdhwU


## Code

(20 points)

For the analysis portion of our code, we decided to extract multiple features including Chroma-based features, spectral centroid, spectral bandwidth, spectral roll off, and zero crossing rate. For our chroma-based features we decided to use 12 (the same amount of coefficents as our MFCCs) and we obtained the mean for all the features among all 29 songs in our database. We then created a dataframe indexed by the political era and further scaled the features to the mean of 0.0 and a standard deviation of 1.0. We then made graphical comparisons among each feature displaying multiple plot graphs to see if there were correlations among each political era. Furthermore to understand the era as a whole, we grouped by political era and obtained the average of every features per decade and displayed subplots to show the growth of features throughout the timeline.

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- data acquisition/scraping
- cleaning
- analysis
- generating results. 

Link each of your notebooks or .py files within this section, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section will contain links to documentation of your results. This can include figures, sound files, videos, bitmaps, as appropriate to your domain of analysis. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`



## Discussion

(30 points, three to five paragraphs)

As for future directions, we defintely think expanding our database would vastly improve results espeically since for some eras they were only represented by two or threee artists. 


The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally relevant?
- How does your computational approach differ from the traditional art historical, musicological, manuel/subjective approach to analyzing your cultural subject? 
- How do you think the original artists/musicians would respond to this type of analysis? Would it change/inform their practice in some way?
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- In what future directions could you expand this work?




## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

References to any papers, techniques, repositories you used:
- Papers
- Repositories
- Blog posts
