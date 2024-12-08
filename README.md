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

<b>Rezultatet e Faza së Parë</b><br>
Dataseti u pastrua dhe u strukturua në mënyrë që të jetë gati për analizat e mëtejshme, duke u fokusuar në cilësinë dhe standardizimin e tij.



### Faza e dytë

  1. Detektimi i përjashtuesit.<br>
  2. Mënjanimi i zbulimeve jo të sakta<br>
  3. Eksplorimi i te dhënave: statistika përmbledhëse, multivariante.<br>

<b>Rezultatet e Faza së Dytë</b><br>
U kuptuan marrëdhëniet mes variablave dhe u identifikuan modele të rëndësishme që ndihmojnë në analizat dhe vizualizimet e mëtejshme.




Në fazën e dytë të projektit, u fokusua në analizimin dhe pastrimin më të thellë të të dhënave. Fillimisht, u realizua detektimi i përjashtuesve (outliers), duke përdorur metoda statistikore për të identifikuar dhe eliminuar vlerat që mund të dëmtonin analizën. Më pas, u mënjanuan zbulimet jo të sakta dhe u trajtuan të dhënat që mund të kishin ndikim negativ në modelet analitike. U realizua eksplorimi i të dhënave përmes statistika përmbledhëse dhe analize multivariante për të kuptuar më mirë marrëdhëniet ndërmjet variablave dhe për të identifikuar mundësi të ndryshimeve dhe modeleve të rëndësishme. 


<h2>Përdorimi</h2>
git clone https://github.com/kaltrinabaliu/PergatitjaDheVizualizimiiTeDhenave.git<br>

<h3>Instaloni librarite e nevojshme</h3><br>

pip install re pandas numpy seaborn matplotlib scikit-learn ipython

