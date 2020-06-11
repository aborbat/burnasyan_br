## EN
breast cancer dataset by Burnasyan Federal Medical Biophysical Center Of Federal Medical Biological Agency (Moscow, Russia)
contains link for 40K+ breast tumor tissue images data set and annotations.
1. for research and education purposes
2. when use, please, quote <<-----------article------------->>
3. short description: contains 42904 images of 12 breast pathology entities with clinical data (age, grade, TNM)
4. data set preparation procedure
>1. slides with breast (female) tissue samples were selected: 91 patients, 104 slides
>2. WSI scanning (Ventana iScan HT, obj 20, pixel size 0,465 μm)
>3. qualified pathologist cropped each WSI for non overlapping regions of interest
>>- x4: size 3750х2750 μm (1633х1185 px)
>>- x10: size 1500х1125 μm (1633х1185 px)
>4. cut region of interest images into 300х300 and 500х500 px:
>>- x4: 0,475 sq mm and 1,318 sq mm
>>- x10: 0,076 sq mm and 0,211 sq mm
>5. images were reviewed by qualified pathologists to withdraw pictures containing <20% pathologically changed epithelia
5. link - <<----------link----------->>
6. annotation file https://github.com/aborbat/burnasyan_br/burnasyan_Br.csv
>- IDX - microscopy slide unique identifier
>-	Num - clinical case unique identifier
>-	age - age
>-	Dia - WHO pathologic classification
>-	Dia2 - type (Benign, InSitu, Invasive)
>-	biopsy - surgery OR biopsy sample
>-	Grade - grade: benign lesions - G0, invasive - Nottingham Histologic Score, DCIS - nuclear grade
>-	TNM - TNM 8: includes pT and pN; if no surgery data - cT и cN
>-	obj10_300 - quantity of images x10; size 300х300 px
>-	obj10_500 - quantity of images x10; size 500х500 px
>-	obj4_300 - quantity of images x4; size 300х300 px
>-	obj4_500 - quantity of images x4; size 500х500 px

## RU
набор данных патологических процессов молочной желез, подготовленный в ФГБУ ГНЦ ФМБЦ им А.И.Бурназяна ФМБА России
содержит ссылку на набор из более 40 тыс изображений и описание
1. только для исследовательских и образовательных целей
2. при использовании набора данных обязательная ссылка на публикацию <<-----------article------------->>
3. краткое описание: содержит 42904 изображения 12 категорий опухолевых и неопухолевых поражений молочной железы с клиническими характеристиками (возраст, TNM, дифференцировка)
4. процедура подготовки набора данных
>1. отобраны микроскопические препараты с патологически измененными тканями молочной железы: 91 пациент, 104 микропрепарата
>2. сканирование (Ventana iScan HT, увеличение объектива 20, размер пикселя 0,465 мкм)
>3. в каждом микропрепарате врач-патологоанатом отбирал непересекающиеся зоны с наличием патологического очага
>>- при увеличении 4 размером 3750х2750 мкм (1633х1185 пикселей), площадью 10,5 кв мм
>>- при увеличении 10 размером 1500х1125 мкм (1633х1185 пикселей), площадью 1,7 кв мм
>4. изображения разделены на квадраты 300х300 и 500х500 пикселей:
>>- при увеличении 4, соответственно, 0,475 кв мм и 1,318 кв мм
>>- при увеличении 10, соответственно, 0,076 кв мм и 0,211 кв мм
>5. изображения повторно просмотрены патологоанатомом: изображения, где железистый компонент патологического очага визуально составлял менее 20% площади изображения, удалялись из набора данных 
5. ссылка на набор изображений - <<----------link----------->>
6. аннотация - https://github.com/aborbat/burnasyan_br/blob/burnasyan_Br.csv
>- IDX - уникальный идентификатор микропрепарата
>- Num - уникальный идентификатор клинического случая
>- age - возраст пациента на момент исследования
>- Dia - морфологический вариант патологического процесса в соответствии с классификацией ВОЗ
>- Dia2 - характер патологического процесса (Benign, InSitu, Invasive)
>- biopsy - операционный (surgery) или биопсийный материал (biopsy)
>- Grade - оценка степени злокачественности: для инвазивных опухолей по Ноттингемским критериям, для протоковой карциномы инситу - по критериям ядерного полиморфизма, G0 соответствует доброкачественным поражениям
>- TNM - классификация случая по системе TNM 8 пересмотра, включены только категории pT и pN, в ряде случаев используется cT и cN, если оперативное вмешательство не проводилось
>- obj10_300 - количество изображений при увеличении 10 и размере 300х300 пикселей
>- obj10_500 - количество изображений при увеличении 10 и размере 500х500 пикселей
>- obj4_300 - количество изображений при увеличении 4 и размере 300х300 пикселей
>- obj4_500 - количество изображений при увеличении 4 и размере 500х500 пикселей
  
  
