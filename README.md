# İzah Etməyim Tələb Olunan Mövzular.
Paradigma nədir?

Proqramlaşdırmada hansı paradigmalar mövcuddur?

İmperative paradigma nədir?

Declarative paradigma nədir?

İmperative və declarative paradigmalar arasındakı ən əhəmiyyətli fərqləri izah edin.

Qeyd: Cavablar Azərbaycan dilində və öz sözlərinizlə yazılmalıdır. 


## Mənim mövzu haqqındakı ətraflı yazımı yuxarıda yerləşdirdiyim faylı açaraq görə bilərsiniz.


&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;**Proqramlaşdırma Paradiqmaları**

Proqramlaşdırma paradiqması, programların həllində istifadə edilən müəyyən bir üsuldur. Burada mən araşdırdığım bir neçə paradiqmanın özəlliklərini sayacam.

<h4>1. Imperative Programming (Zəruri Proqramlaşdırma)</h4>
<ul>
<li>Object-oriented Programming (Obyekt-yönümlü Proqramlaşdırma)</li>
<li>Parallel Processing/Computing (Paralel hesablama)</li>
<li>Procedual Programming (Prosedur Programlaşdırma)</li>
</ul>

<h4>2. Imperative Programming (Zəruri Proqramlaşdırma)</h4>
<ul>
<li>Functional Programming (Funksional Proqramlaşdırma)</li>
<li>Logic Programming (Məntiqi Proqramlaşdırma)</li>
<li>Dataflow Programming (Məlumat axınlı Proqramlaşdırma)</li>
</ul>

1. İmperative Programming
Bu paradigmanı izah etmək üçün bir misal çəkəcəm. Məsələn arrayın içində 1-10 arası rəqəmlər var və mən 1-10 arası olan bütün cüt rəqəmləri ekrana çıxarmaq istəyirəm.

```
var array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
var reqem;
for (a = 0; a < array.length; a++) {
    var reqem = array[a]/2;
    if(reqem % 1 == 0){   
      console.log(array[a]);
    }
}

```

1. array adında bir Array yaradıram.
2. Rəqəm adlı dəyişgən yaradıram.
3. For döngüsünü başladıb arrayın index sayından kiçik olana qədər (0-9 index) for döngüsünü təkrar etdirirəm.
4. For döngüsünün içində, arrayın check edilən indeksinin dəyərini bölüb rəqəm adlı dəyişgənimə bərabər edirəm.
5. if şərtində % operatorunun köməyi ilə "əgər reqem deyişgeni bölünüb tam sayısı alınanda bərabərdirsə 0-a, arrayın a indexinin dəyərini console'da göstər.

* Object-oriented Programming 
Obyekt yönümlü programlaşdırma paradigması olan bütün dillərdə mənim fikrimcə array vardır. Çünkü belə başa düşürəm ki, arrayın özüdə içində bir çox məlumatı indeksləyərək tutduğu üçün bir obyektdir. Sizin 2015 ci ildə çəkdiyiniz misaldakı kimi, array bir sinifdir və içindəki indekslər sinifdəki şagirdlərdir. array içində array yaradaraq onun içinə şagirdləri yerləşdirmək isə, məktəbin içindəki 10 sinifin hərəsində 5-6 tələbə var deməkdir. OOP, biz programçıların işlərini asanlaşdırır. Belə düşünürəm ki, OOP'nin Functional Paradiqma ilə ortaq bir özəlliyi odur ki, OOP paradigması bir özəlliyi ilə Functional paradigmaya bənzəyir. Eyni kodu təkrar-təkrar bir neçə yerdə yazmağın qarşısını alır. Lakin OOP verilən əmrləri təkrar etmir. Sadəcə müəyyən məlumatları classlarda saxlayır və lazım olduqda o classdan çəkmək olur həmin dəyərləri. Class sayəsində də, müxtəlif yerlərdə eyni məlumatı çəkmək üçün databaza ilə bağlantı qurmaq əvəzinə, bir dəfə bağlantı qurub Classın içindəki məlumatı çağırmaq olar. Wiki'dən aldığım məlumata görə OOP 1960-cı illərin sonunda, applicationun həcmini və qarışıqlığını ən az səviyyəyə endirmək məqsədilə yaradılıb. Kim yaradıb onu dayy sormayın hocam :) kim yaradıbsa Allah canını sağ eləsin deyək )

* Parallel Programming
Paralel  programlaşdırma böyük əmrlərin  və ya böyük problemlərin hissələrə bölünərək həll edilməsidir. Paralel paradigma sayəsində bir əmri  bir neçə hissəyə bölüb  ən əsasıda böldüyümüz hissələri eyni anda işə salmağa müvəffəq oluruq. Əgər Paralel programlaşdırma ilə etməsəydik, bu böyük əmri bir dəfəyə verdiyimiz və ya hər hansı böyük bir əməliyyatı hissələrə bölmədən bütöv bir şəkildə icra etdiyimiz üçün komputer bu tək və böyük əmri çətinliklə yerinə yetirəcəkdi. Lakin, əmri hissələrə bölüb "hadi koçum, yap şimdi " dediyimiz anda komputer bu bölünmüş bəsit əmrləri asanlıqla yerinə yetirir və təkrar edirəm, ən əsasıda bir neçə əmri eyni anda sıraya qoymadan yerinə yetirməklə bizə vaxt qazandırır. Sizin dərsdə çəkdiyiniz misala bənzəyir bu. Siz videonu 1 komputerdə save və ya convert etdiyinizə görə, komputer əməliyyatın təxmini bitmə müddətinin 1-2 həftə olduğunu hesablayıb. Lakin, siz həmin videonu göndərmisiniz almaniyada bir neçə ayrı komputerdə daha sürətli bir şəkildə etmisiniz.

* Procedual Programming
Procedual programlaşdırma anladığım qədərilə functional kimidir. Hətta funksiyalara, altyordama və ya altprograma dayanır. Amma ki, daha çox riyazi funksiyaları Procedual Programminglə yerinə yetirmək mümkün olur. Məsələn bir marketdə alıcının aldığı məhsulun barkodunu satıcı barkod oxuyucu vasitəsilə programa tanıdır. İndiki fresco marketlərdə hətta ən ara məhəllələrdə belə maşallah məhsulun adı, tarixi, endirim faizi, hansı şirkətə məxsus olduğu vs. vs. hamısı çıxır. Burda barkod oxuyucuda biz Procedual Programming ilə, faizi hesablamaq, müştərinin verdiyi 10 manatdan 2 manat məhsulun dəyərini çıxıb, qaytaracağımız zdaçinin 8 manat olduğunu hesablamaq kimi şeylərdir. Hansı şirkətə məxsus olduğu, satıcının adı falan filan onları isə Functional Programminglə edirik. Birdəki Hocam bir şeyi anlamadım düzü, araşdırmalarda belə bir məlumat əldə etdim ki, Functional programla bir neçə funksiya arasında əlaqə yaratmaq, iki functionu birləşdirmək falan mümkün olur. Amma bu procedual da olmur. Zənnimcə bəlkədə toplama çıxma kimi functionları yerinə yetirir. Amma normal bildiyimiz function kimi bir neçə yerdə çağırıla bilir funksiyalar procedual programmingdə.

2. Declarative Programming 
Declarative programlaşdırma araştırmalarımdan bu nəticəni çıxardım ki, məsələn XAML ilə bir button əmələ gətirmək üçün:
	<button name="my_btn" width="120 height="120">Klik et</button>
yuxarıdakı kodu yazırıq. Lakin Declarative olan C# ilə sanki qruery ilə bir buttonun attributuna müdaxilə edərmişcəsinə müdaxilə edirik Hocam :)
Button my_btn1= new Button(); 
my_btn1.Content = "Klik et"; 
my_btn1.Width = 120; 
my_btn1.Height = 120;
Birdə deyəxən XML də Declarative paradigma yöntəmi ilə yazılır. Çünkü examplelər arasında var olmayan html kodları gördüm. Misal üçün:
	<mekteb>
		<sinif></sinif>
		<sinif></sinif>
	</mekteb>

* Functional Programming
Functional programlaşdırma həyatdır :) Yuxarıda qeyd etmişdim ki, OOP paradigması bir özəlliyi ilə Functional paradigmaya bənzəyir. Eyni kodu təkrar-təkrar bir neçə yerdə yazmağın qarşısını alır. Lakin OOP verilən əmrləri təkrar etmir. Sadəcə müəyyən məlumatları siniflərdə saxlayır və lazım olduqda o sinifdən çəkmək olur həmin dəyərləri.Functional paradigmada isə, səhifəmdə 5 yerdə istifadə edəcəyim toplama işləmini, funksiyanın argumentlərini dəyişərək edə bilərəm. Məsələn:
function test(a,b){
  a=a+b;
  console.log(a);
}
test(5,4);
test(15,5);
test(25,6);
