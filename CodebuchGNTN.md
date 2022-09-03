    # Datensatz GNTN #
    Codebuch Stand 2022-06, 
    erstellt von Swaran Sandhu (sandhu@hdm-stuttgart.de)

    ## Inhalt
    - Edges.csv (Edgelist)
    - Nodes.csv (Nodelist)
    - Codebuch.md (Codierung der Datensätze)

    ## Ursprung und Datenerhebung
   Wir erheben einen Datensatz der Top 3 Finalistinnen der vergangenen 16 Staffeln Germays Next Topmodel, um herauszufinden, ob die Kandidatinnen nach der  Teilnahme an der Sendung beruflichen Erfolg in der Modelbranche erzielen. Die Daten entstammen einer gründlichen Internetrecherche.

    Das Netzwerk ist ein *ungerichtetes two-mode Akteursnetzwerk*. 
      
    **Umgang mit fehlgenden Werten**
    Fehlende Werte werden nicht erfasst.
    
    **herausgelassene Daten**

    # EDGE-Attribute

    **from**
    Knoten, in diesem Fall: Kandidatinnen aus jeweiliger Staffel 

    **to**
    Knoten, in diesem Fall: Kandidatinnen stehen in Arbeits-/Liebesverhältnis mit jeweiligem Knoten. 
    Beispielsweise:
    - Modelagenturen
    - TV shows und Filme
    - Berufe ohne Öffentlichkeitsauftritt
    - Romantische Beziehung mit Personen des öffentlichen Lebens
    - Werbekampagnen
    - Soziale-Netzwerk-Plattform (z.B. Instagram, Twitter, Tiktok)
    
    Wir erfassen unter diesen Punkt alle Akteure die Einfluss auf den Werdegang der Kandidatinnen haben oder hatten.
    
    **year**
    Jahr, in dem die jeweilige Beziehung stattgefunden hat.
    
    **relationship**  
    candidate = Teilnehmenrin oder Kandidatin einer TV Show (Reality-TV-, Quiz-, Talent-, Castingshows)
    contract = Vertragsbeziehung der (ehem.) Kandidatin und dem Knoten (z.B. Verträge zwischen Model und Agentur)
    host = Moderation einer TV Show (Reality-TV-, Quiz-, Talent-, Castingshows) 
    jury = Juror einer Casting-/Wettbewerb Show 
    voice actor = Synchronsprecherin in Filmen oder ähnlichem
    actor = Schauspielerin/Gast- oder Nebenrolle in Filmen oder Serien
    founder = Gründerin (z.B. eigenes Modelabel, Online Magazin, Unternehmen)
    ambassador = Botschafterin oder Gesicht einer Marke
    job = Berufe ohne Öffentlichkeitsauftritt
    influencer = Influencer, ab 50 Tausend Abonnenten
    love = romatische Beziehung
    
    **sector**
    tv show = Shows, die im Fernsehen ausgestrahlt werden (Reality-TV-, Quiz-, Talent-, Castingshows, TV Serien)
    modeling = Alle Beschäftigungen, die in der Modebranche stattfinden
    fashion = Alle Knoten, die in der Kleidungs-/Accessoiresbranche liegen
    movie = Alle Knoten der Filmindustrie
    event = Event
    music video = Kandidatinnen, die teil eines Musikvideos waren
    advertisement = Werbekampagnen
    journalism = journalistische Beschäftigungen
    social media = Soziale-Netzwerke
    
    **channel**
    Alle Sender auf denen die jeweiligen Shows/Serien liefen und mit denen die Kandidatinnen womöglich assoziiert werden.
    - Pro7
    - Puls4 (Österreich)
    - RTL
    - SAT1
    - ARD
  

    # NODE-Attribute  
      
    **id**  
    Identische ID wie aus der edgelist zur Identifikation der Knoten.

    **name**
    Vollständiger und ausgeschriebener Name (der Kandidatin/Agentur/Marke...)

    **name_short**
    Vorname abgekürzt, z.B. für Visualiserung, falls der Name zu lange ist
    
    **type**
    model = Kanditatin von GNTM
    tv = Shows, die im Fernsehen ausgestrahlt werden (Reality-TV-, Quiz-, Talent-, Castingshows, TV Serien)
    agency = Agentur, bei der die jeweilige Kandidatin unter Vertrag steht
    magazine = Magazin
    event = Event/Veranstaltung
    movie = Film
    brand = eigene Marke der Kandidatin
    streaming = Plattformen, auf denen Straming erfolgt (z.B. Netflix, Prime Video, maxdome)
    job = Berufe ohne Öffentlichkeitsauftritt
    soccer player = Fußballspieler, der in Beziehung mit Kandidatin steht
    

    **birth year**    
    Geburtsjahre der einzelnen Kandiatinnen.
    
      
    **sex***    
    weiblich
    männlich
    divers

    **hair**  
    Haarfarbe, aus dem jeweiligen Staffelfinale:
    black
    brown
    blonde
    red
    coloured

    **skin**  
    Hautfarbe:
    light
    medium
    dark
    
    **place of birth**   
    Geburtsort der Kandidatin.
    
    **nationality**   
    Nationalität der Kandidatin

    **ethnicity**    
    Herkunft der Kanditation nach Land
      
    **follower_insta**    
    Anzahl der Follower auf Instagram in tausender Schritten. (Stand:2022)
 
    **follower_tiktok**  
    Anzahl der Follower auf TikTok in tausender Schritten. (Stand:2022)
      
    **market_cap**    
    Marktwert der Kandidatin 

    **season_gntm**  
    jeweilige Staffel der Kandidatin

    **place_gntm** 
    Platzierung der Kandidatin bei GNTM. 
    1 = 1. Platz
    2 = 2. Platz
    3 = 3. Platz

    ##
