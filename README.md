# SEGMENTAZIONE-DELLA-CLIENTELA-PER-ATTIVITA-DI-MARKETING

## Descrizione del progetto
In questo progetto ho analizzato il comportamento di utilizzo di circa 9.000 titolari di carte di credito per identificare segmenti di clientela distinti. L'obiettivo è fornire raccomandazioni strategiche per campagne di marketing mirate, ottimizzando il budget e migliorando l'engagement dei clienti.

Il progetto applica tecniche di Apprendimento Non Supervisionato (Clustering) per raggruppare i clienti in base a abitudini di spesa, frequenza di utilizzo e affidabilità nei pagamenti.

## Tecniche utilizzate

*Data Cleaning*: gestione valori mancanti tramite imputazione della mediana e rimozione degli outlier logaritmici.

*Feature Engineering*: standardizzazione dei dati con StandardScaler.

*Riduzione della dimensionalità*: utilizzo della PCA (Principal Component Analysis) per spiegare l'85% della varianza e migliorare le performance del clustering.

*Clustering*: algoritmo K-Means, ottimizzato tramite Elbow Method (Inertia) e Silhouette Score per la validazione della coesione dei cluster.

*Visualizzazione*: Seaborn, Matplotlib e Radar Charts per il profiling comportamentale.

## Risultati e Cluster Identification
L'analisi ha identificato 4 profili chiave:

- Cluster premium: clienti con saldo elevato e pagamenti puntuali. Ideali per programmi fedeltà esclusivi.

- Installment shoppers: clienti che preferiscono acquisti rateizzati. Target perfetto per offerte su piani di finanziamento.

- Cash advance users: soggetti che richiedono spesso anticipi di contante (profilo a rischio più elevato). Richiedono monitoraggio del credito.

- Low activity: clienti con bassa frequenza d'uso. Target per campagne di riattivazione con sconti o incentivi.


Ho incluso una simulazione di impatto delle campagne calcolando **expected conversions**, **estimated ROI per segmento** e **costi di acquisizione vs. ricavi attesi**

## Per utilizzare il progetto
Una volta clonato il progetto, per utilizzarlo assicurati di avere il file credit_card_customers.csv nella root del progetto e avvia lo script.
Il database lo puoi trovare all'interno della repository.
