# Pytorch Pneumonia localization

![Open In Colab](https://colab.research.google.com/drive/1GrPVEx9jKmnbrqrtnn2SrMiGC0iRMx66?usp=sharing)

Background:
In screening for Covid-19, patients can first be screened for flu-like symptoms using nasal swap to confirm their COVID-19 status. After 14 days of quarantine for confirmed cases, the hospital draws the patient’s blood and takes the patient’s chest X-ray. Chest X-ray is a golden standard for physicians and radiologists to check for the infection caused by the virus. An x-ray imaging will allow your doctor to see your lungs, heart and blood vessels to help determine if you have pneumonia. When interpreting the x-ray, the radiologist will look for white spots in the lungs (called infiltrates) that identify an infection. This exam, together with other vital signs such as temperature, or flu-like symptoms, will also help doctors determine whether a patient is infected with COVID-19 or other pneumonia-related diseases. The standard procedure of pneumonia diagnosis involves a radiologist reviewing chest x-ray images and send the result report to a patient’s primary care physician (PCP), who then will discuss the results with the patient. Alt text

_Fig 4: Chart of wait-time reduction of AI radiology tool (data from a simulation stud reported in Mauro et al., 2019). _

A survey by the University of Michigan shows that patients usually expect the result came back after 2-3 days a chest X-ray test for pneumonia. (Crist, 2017) However, the average wait time for the patients is 11 days (2 weeks). This long delay happens because radiologists usually need at least 20 minutes to review the X-ray while the number of images keeps stacking up after each operation day of the clinic. New research has found that an artificial intelligence (AI) radiology platform such as our CovidScan.ai can dramatically reduce the patient’s wait time significantly, cutting the average delay from 11 days to less than 3 days for abnormal radiographs with critical findings. (Mauro et al., 2019) With this wait-tine reduction, patients I critical cases will receive their results faster, and receive appropriate care sooner.

