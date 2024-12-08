![image](https://github.com/user-attachments/assets/a2e1ad8f-ead5-49b7-9a15-b17c7e52be35)

<h1>Analizë e të dhënave të kredive</h1>
Emri i projektit: Analizë e të dhënave të kredive <br>
Lënda: Përgatitja dhe Vizualizimi i të Dhënave <br>
Mentor: Prof.Dr.Mërgim Hoti <br>
Universiteti: Universiteti i Prishtinës "Hasan Prishtina" <br>
Fakulteti: Fakulteti i Inxhinierisë Elektrike dhe Kompjuterike, Programi Kompjuterik, 2024/25


<h2>Përmbledhja e projektit</h2>

Ky repository përmban projektin semestral për lëndën "Përgatitja dhe Vizualizimi i të Dhënave," i realizuar në tri faza nën mentorimin e Prof. Mërgim Hoti, në kuadër të semestrit. Projekti ka për qëllim analizimin e të dhënave të kredive, duke përdorur teknika të avancuara të përgatitjes dhe vizualizimit të të dhënave. Përmes këtij projekti, janë aplikuar metoda të ndryshme për të pastruar dhe strukturuar të dhënat, duke përfshirë trajtimin e vlerave të humbura dhe anomalive.

Përveç përgatitjes, janë zhvilluar vizualizime interaktive që ndihmojnë në identifikimin e modeleve dhe trendeve të rëndësishme. Përfundimet e nxjerra nga analiza synojnë të përmirësojnë proceset e vendimmarrjes në sektorin e kredive, duke ndihmuar në vlerësimin më të saktë të riskut dhe përcaktimin e strategjive të qëndrueshme financiare. Projekti shërben si një shembull praktik i aplikimit të shkencës së të dhënave në një kontekst të jetës reale

<h2>Dataset i perdorur per analizim</h2>
Dateseti përmban informacione të detajuara mbi aplikimet për kredi, duke përfshirë këto kolona:

 
<strong>LoanID</strong>: Identifikues unik për çdo aplikim për kredi.<br>
<strong>ApplicantID</strong>: Identifikues unik për çdo aplikant.<br>
<strong>ApplicantGender</strong>: Gjinia e aplikantit.<br>
<strong>ApplicantMarried</strong>: Statusi martesor i aplikantit.<br>
<strong>ApplicantDependents</strong>: Numri i personave në ngarkim të aplikantit.<br>
<strong>ApplicantEducation</strong>: Kualifikimi arsimor i aplikantit.<br>
<strong>ApplicantSelfEmployed</strong>: Statusi i punësimit të aplikantit.<br>
<strong>ApplicantIncome</strong>: Të ardhurat e aplikantit.<br>
<strong>ApplicantCreditHistory</strong>: Historia e kredisë së aplikantit.<br>
<strong>ApplicantZIP</strong>: Kodi ZIP i aplikantit.<br>
<strong>ApplicantState</strong>: Shtetesia e aplikantit.<br>
<strong>ApplicantEmpLength</strong>: Gjatesia e punesimit te aplikantit. <br>
<strong>ApplicantHomeOwn</strong>: Posedimi i ndonje objekt banimi. <br>
<strong>LoanAmount</strong>: Shuma e kredisë së kërkuar.<br>
<strong>LoanTerm</strong>: Kohëzgjatja e kredisë.<br>
<strong>LoanIntRate</strong>: Norma e interesit për kredinë.<br>
<strong>LoanDesc</strong>: Pershkrimi per kerkesen per kredi. <br>
<strong>LoanPurpose</strong>: Qëllimi për të cilin merret kredia.<br>
<strong>LoanApproved</strong>: Nëse kredia është miratuar apo jo. <br>


Ky projekt përdor këtë dataset për të ndihmuar në krijimin e modeleve dhe përmbledhjeve të të dhënave që mund të ndihmojnë në analizimin dhe vendimmarrjen për kreditë.
Projekti përdor Python për analizën dhe vizualizimin, duke përfshirë biblioteka si Pandas, Matplotlib, Scipy, Missingno dhe Seaborn.

<h2>Faza e parë</h2> 

  1. Para-procesimi për përgatitjen e të dhënave për analizë.<br>
  2. Mbledhja e të dhënave, definimi i tipeve të dhënave, kualiteti i të dhënave.<br>
  3. Integrimi, agregimi, mostrimi, pastrimi, identifikimi dhe strategjia e trajtimit për vlerat e zbrazëta.<br>
  4. Reduktimi i dimensionit, zgjedhja e nën bashkësisë së vetive, krijimi i vetive, diskretizimi dhe binarizimi, transformimi.<br>

Gjatë fazës së parë të projektit, u krye përgatitja e dataset-it për analizë përmes para-procesimit dhe pastrimit të të dhënave. Fillimisht, u analizua struktura dhe cilësia e dataset-it, duke trajtuar vlerat e zbrazëta përmes metodave si zëvendësimi ose heqja e tyre. U përcaktuan tipet e të dhënave dhe kategorizuan veçoritë, ndërsa reduktimi i dimensionit u realizua duke përzgjedhur kolonat më të rëndësishme. Gjithashtu, u krijuan veçori të reja dhe u zbatuan transformime si diskretizimi dhe normalizimi për standardizimin e dataset-it. <br>

<b>Rezultatet e Fazës së Parë</b><br>
Dataseti u pastrua dhe u strukturua në mënyrë që të jetë gati për analizat e mëtejshme, duke u fokusuar në cilësinë dhe standardizimin e tij.

![image](https://github.com/user-attachments/assets/28433d02-65d9-452a-bd26-26c040ef4539) <br>
![image](https://github.com/user-attachments/assets/94827ab0-142b-435f-875c-19a916f30974) <br>





### Faza e dytë

  1. Detektimi i përjashtuesit.<br>
  2. Mënjanimi i zbulimeve jo të sakta<br>
  3. Eksplorimi i te dhënave: statistika përmbledhëse, multivariante.<br>

<b>Rezultatet e Fazës së Dytë</b><br>
U kuptuan marrëdhëniet mes variablave dhe u identifikuan modele të rëndësishme që ndihmojnë në analizat dhe vizualizimet e mëtejshme.




Në fazën e dytë të projektit, u fokusua në analizimin dhe pastrimin më të thellë të të dhënave. Fillimisht, u realizua detektimi i përjashtuesve (outliers), duke përdorur metoda statistikore për të identifikuar dhe eliminuar vlerat që mund të dëmtonin analizën. Më pas, u mënjanuan zbulimet jo të sakta dhe u trajtuan të dhënat që mund të kishin ndikim negativ në modelet analitike. U realizua eksplorimi i të dhënave përmes statistika përmbledhëse dhe analize multivariante për të kuptuar më mirë marrëdhëniet ndërmjet variablave dhe për të identifikuar mundësi të ndryshimeve dhe modeleve të rëndësishme. 

### Kontrolli i të Dhënave të Humbura

Kjo pjesë përfshin përdorimin e një heatmap për të identifikuar vlerat e humbura në DataFrame. Heatmap-i vizualizon mungesat e të dhënave, duke ndihmuar në identifikimin e kolonave që kanë probleme me të dhënat e plota.
![image](https://github.com/user-attachments/assets/a8d0f572-177e-43e5-a256-67b586853b6a)
![image](https://github.com/user-attachments/assets/ac3916d2-d401-4c05-a7a1-17752a662a25)

### Vizualizimi i Shpërndarjes

Këtu, krijohen grafikë të tipit KDE (Kernel Density Estimate) dhe box plot për të analizuar shpërndarjen e kolonave numerike vizualizime ndihmojnë në kuptimin e shpërndarjes, asimetrisë dhe pranishmërisë së outlier-eve në të dhëna.
![image](https://github.com/user-attachments/assets/65367391-fd56-49b0-a9e4-05970c7e96b3)
![image](https://github.com/user-attachments/assets/cfb83fd9-b652-440d-991e-7faddd64d08a)
![image](https://github.com/user-attachments/assets/a878c527-f663-4807-af2c-1e1ee57d349b)
![image](https://github.com/user-attachments/assets/78b92028-e0cb-45cc-b0b6-5791517b26aa)
![image](https://github.com/user-attachments/assets/6857079a-4800-4866-9981-04bb6aca1a40)
![image](https://github.com/user-attachments/assets/ce9772b8-e67b-4101-baab-35fff3138aca)
![image](https://github.com/user-attachments/assets/71256329-82a7-4488-8402-8886d8577b47)
![image](https://github.com/user-attachments/assets/94381574-b442-4bed-b970-2390d93f38d9)
![image](https://github.com/user-attachments/assets/2e4fd0c9-cff4-47b4-bc21-8c92d7254fdb)
![image](https://github.com/user-attachments/assets/edb9c058-0295-435b-a297-757b9804ff19)
![image](https://github.com/user-attachments/assets/391807e9-4565-438b-9644-0051f4df4c7e)

### Outliers (Të Jashtme)

Kjo pjesë e dokumentit përqendrohet në identifikimin dhe analizimin e outlier-eve në të dhënat e përfshira në DataFrame. Outlier-ët janë vlera që ndahen ndjeshëm nga shumica e të dhënave dhe mund të ndikojnë në rezultatet e analizave statistikore.

### Identifikimi i Outlier-eve

Përdoren grafikët box plot dhe KDE për të identifikuar outlier-et në kolonat numerike si LoanAmount dhe ApplicantIncome. Këto vizualizime ndihmojnë në identifikimin e vlerave që janë shumë më të larta ose më të ulëta se shumica e të dhënave. <br>
![image](https://github.com/user-attachments/assets/3be18974-8aa0-4fbb-b6d3-26360bd85dff) <br>

### Analiza para dhe pas pastrimit

Dokumenti përfshin një krahasim të shpërndarjes së të dhënave para dhe pas pastrimit të outlier-eve. Kjo ndihmon në vlerësimin e ndikimit të outlier-eve në analizat e të dhënave dhe në rezultatet përfundimtare.

![image](https://github.com/user-attachments/assets/766564da-a715-4673-91f7-647d9893cdf1) <br>
![image](https://github.com/user-attachments/assets/8317a1c7-25b2-47f9-aac0-02621ad42f22) <br>
![image](https://github.com/user-attachments/assets/c9284df2-18b0-48a3-9691-a60a7b925a77) <br>
![image](https://github.com/user-attachments/assets/beac1d5a-66df-4194-932b-bf622c397d04) <br>
![image](https://github.com/user-attachments/assets/0eb6d016-9b82-47c3-a2db-bdf8511cfb58) <br>
![image](https://github.com/user-attachments/assets/03348777-b983-4c94-a24e-8ed27914ab97) <br>

### Analiza e Korrellacionit

Kjo pjesë përfshin përdorimin e një heatmap për të vizualizuar korrelacionin midis kolonave numerike. Korrrelacioni ndihmon në identifikimin e marrëdhënieve midis variablave, duke treguar se si ndryshimi në një variabël ndikon në një tjetër. <br>
![image](https://github.com/user-attachments/assets/ec2e0560-3d7a-4cdd-9f24-b05da76df00a)

### Scatter Matrix

Funksioni "plotScatterMatrix" krijon një matricë scatter për të vizualizuar marrëdhëniet midis karakteristikave numerike në dataset. Kjo ndihmon në identifikimin e modeleve dhe marrëdhënieve të mundshme midis variablave. <br>
![image](https://github.com/user-attachments/assets/05ddfe78-7ecc-44df-ac02-026b58003e8d)

### Statistika për Kolonat Numerike

Këtu llogariten mesatarja, devijimi standard dhe percentile të ndryshme për LoanAmount. Kjo ofron një pasqyrë të qartë mbi shpërndarjen dhe karakteristikat e të dhënave numerike.
Shembull: 

Mesatarja e LoanAmount: 44636.36517422083<br>
Devijimi standard i LoanAmount: 15638.731039560082<br>
Percentilet e LoanAmount: <br>
0.25    35000.0<br>
0.50    43750.0<br>
0.75    53900.0<br>
Name: LoanAmount, dtype: float64<br>

### Testet Statistike

Kjo pjesë përfshin kryerjen e testeve ANOVA dhe T-test për të analizuar diferencat midis grupeve të ndryshme bazuar në të dhënat e aplikantëve. Këto teste ndihmojnë në vlerësimin e rëndësisë statistikore të diferencave midis grupeve.
![image](https://github.com/user-attachments/assets/79934e39-a182-4ffe-bf8e-cf20daa47401)<br>

Rezultati ANOVA - p-value: 0.19681765332366513<br>
![image](https://github.com/user-attachments/assets/ad09b6fd-1969-4116-b909-29d9922fdec8)<br>

T-statistic: -0.13768594006621337, P-value: 0.8904899061666572

### Skewness dhe Kurtosis

Këtu llogariten asimetria (skewness) dhe kurtosis për LoanAmount. Këto metrika ndihmojnë në kuptimin e formës së shpërndarjes së të dhënave, duke treguar nëse shpërndarja është e përkulur në njërën anë ose ka tail të gjatë.
![image](https://github.com/user-attachments/assets/cd505586-7996-4e6c-b9af-03eecc9c6d7a)<br>

Asimetri: 0.29208597542419057<br>
Kurtosi: 0.22453439515223206<br>
![image](https://github.com/user-attachments/assets/bf64504d-b435-4a48-b6a8-f5c09d11ef33)<br>
ANOVA F-statistic: 0.3407759020275155, P-value: 0.5593877516162054

### Statistika Përmbledhëse

Kjo pjesë ofron statistika përmbledhëse për kolonat numerike si ApplicantIncome, LoanAmount, dhe LoanIntRate. Ajo përfshin të dhëna si mesatarja, median, devijimi standard, minimumi dhe maksimumi, duke ofruar një pasqyrë të plotë mbi karakteristikat e të dhënave.
![image](https://github.com/user-attachments/assets/9b117b98-91da-441d-ba0d-5c5ef2c77378) <br>
### Statistikat përmbledhëse për kolonat numerike
![image](https://github.com/user-attachments/assets/8cda8c14-0435-4bed-8c8d-5a094483321a) <br>

### Analiza e Korrellacionit ne mes kolonave te caktuara numerike
![image](https://github.com/user-attachments/assets/d7f4eac2-b03f-4593-a0c0-4524c29dd992) <br>
![image](https://github.com/user-attachments/assets/aa5d73c5-1a28-4630-95c7-5232fa231bd9) <br>


<h2>Përdorimi</h2>
git clone https://github.com/kaltrinabaliu/PergatitjaDheVizualizimiiTeDhenave.git <br>

<h3>Instaloni librarite e nevojshme</h3><br>

pip install re pandas numpy seaborn matplotlib scikit-learn ipython<br>

Run the project

