



=! Quality !=

====  ====

<[center]
<<<images/BadTitleQuality.png,height=5cm>>>
[center]>


====  ====

<[columns]

[[[0.7\textwidth]]]

<[center]
<<<images/BadTitleQuality.png,height=4cm>>>
[center]>


[[[0.6\textwidth]]]

<[center]
<<<images/TitleQualityProblems.png,height=4cm>>>
[center]>

[columns]>



====  ====

<[center]
<<<images/TechdebtEightDimQuality.png,height=8cm>>>
[center]>


=! Quality : Further reading !=



====  ====

<[center]
<<<images/ZenAndMaintenance.png,height=8cm>>>
[center]>


====  ====

<[center]
<<<images/QualityBidness.png,height=8cm>>>
[center]>


====  ====

Things to google and people to follow

* People
** Dr. Deming
** Eliyahu Goldratt

* Practices
** TQM
** Kaizen



=! Code Quality !=


====  ====

<[center]
<<<images/TechdebtEightDimQuality.png,height=8cm>>>
[center]>


====  ====

<[center]
<<<images/CodeQualityJustOne.png,height=8cm>>>
[center]>



====  ====

<[center]
<<<images/CodeQualitySix.png,height=8cm>>>
[center]>



====  ====

<[center]
<<<images/CodeQualityRemainingTwo.png,height=8cm>>>
[center]>




=! Technical Debt !=

====  ====

<[center]
<<<images/SlowerToImplFeature.pdf,height=6cm>>>
[center]>


=! Why? !=

=! What does software engineer do? !=

=! Write code? !=

=! Not really !=


==== {Tidelift survey}(((\url{https://bit.ly/2XDexFO})))  ====

<[center]
<<<images/tidelift_breakdown.png,height=6cm>>>
[center]>



==== {Quora question}(((\url{https://bit.ly/2ZIZUDt})))  ====

<[center]
<<<images/quora_question.png,height=3cm>>>
[center]>

==== {Quora question}(((\url{https://bit.ly/2ZIZUDt})))  ====



<[columns]

[[[0.7\textwidth]]]

<[center]
<<<images/quora_question.png,height=2cm>>>
[center]>


[[[0.6\textwidth]]]

Typical answer

* 80-90 \% reading
* 20-10 \% writing

[columns]>

==== {Robert Martin (Uncle Bob)}(((\url{https://bit.ly/3c4BPtb})))  ====

<[center]
<<<images/UncleBobQoute1.png,height=5cm>>>
[center]>

==== Amdahl's Law ====

$$
S = \frac{1}{(1-p)+\frac{p}{s}}  
$$

Where:

$p$  - portion of whole to speed up

$s$  - speed up factor


==== Amdahl's Law ====

<[columns]

[[[0.5\textwidth]]]


$$
S = \frac{1}{(1-p)+\frac{p}{s}}  
$$

Where:

$p$  - portion of whole to speed up


$s$  - speed up factor

[[[0.6\textwidth]]]

* Optimistic assumption 80\% reading 20\% writing
* Speed up factor of 2
* Double the speed to write code $ \rightarrow $ 10\% overall improvement
* Double the speed to read code $ \rightarrow $ 60\% overall improvement


[columns]>


=! So, how do we speed it up? !=

==== What's slows us down? ====

* Bad code structure
* Copy-pasta
* Lack of architecture
* Lack of common style
* Lack of unit tests (integration, end-to-end)


==== Bad structure : Spaghetti Code  ====

<[columns]

[[[0.7\textwidth]]]

<[center]
<<<images/pasta.jpg,height=4cm>>>
[center]>


[[[0.6\textwidth]]]


<[center]
<<<images/spaghetti_code.jpg,height=6cm>>>
[center]>

[columns]>



==== Bad structure : Ravioli Code  ====
s
<[columns]s

[[[0.4\textwidth]]]

<[center]
<<<images/gnocchi.jpg,height=3cm>>>
[center]>


[[[0.5\textwidth]]]

* 100s or 1000s of classes
* No coherence
* Each code change affects 30-40 classes
* Did we break anything by the change?

[columns]>



==== Bad structure : Lasagna Code  ====

<[columns]

[[[0.7\textwidth]]]

<[center]
<<<images/lasagna.jpg,height=4cm>>>
[center]>


[[[0.6\textwidth]]]

* A lot of layers
* Hard to comprehend what happens where
* Hard to understand impact of the change


[columns]>



==== Copy Pasta  ====

<[columns]

[[[0.4\textwidth]]]

<[center]
<<<images/copypasta.jpg,height=4cm>>>
[center]>


[[[0.6\textwidth]]]

* Need new method similar to existing one
* NO PROBLEMO!
* Copy paste existing method
* Rename and modify


[columns]>
