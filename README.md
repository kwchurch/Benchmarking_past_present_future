<html>
  <body>
<h1>Workshop Home Page for Benchmarking: Past, Present and Future</h1>

Where have we been, and where are we going?  It is easier to talk about the past than the future. These days,
benchmarks evolve more bottom up (such as papers with code). There used to
be more top-down leadership from government (and industry, in the  case of
systems, with benchmarks such as <a href="https://www.spec.org/benchmarks.html">SPEC</a>). Going forward, there may be more
top-down leadership from organizations like <a href="https://mlperf.org/"> MLPerf </a> and/or influencers like
<a href="https://en.wikipedia.org/wiki/David_Ferrucci"> David Ferrucci </a>, who was responsible for IBM’s success with <a href="https://www.youtube.com/watch?v=P18EdAKuC1U">Jeopardy</a>, and
has recently written a paper suggesting how the community should think
about benchmarking for machine comprehension (<a href="https://arxiv.org/pdf/2005.01525.pdf">To Test Machine Comprehension, Start by Defining Comprehension</a>). Tasks such as reading
comprehension become even more interesting as we move beyond English.
Multilinguality introduces many challenges, and even more opportunities.

We have an amazing collection of invited speakers that can share with us first hand knowledge of how benchmarking became important in Information Retrieval, and then in speech (starting around 1975), and then in language (in 1988).  Much of this history is described in this video and two 2016 Interspeech keynotes: Makhoul describes how benchmarking overcame resistance in speech in <a href="https://www.superlectures.com/interspeech2016/isca-medalist-for-leadership-and-extensive-contributions-to-speech-and-language-processing">this keynote</a>, and Jurafsky describes how this approach moved from speech to language in <a href="https://www.superlectures.com/interspeech2016/ketchup-interdisciplinarity-and-the-spread-of-innovation-in-speech-and-language-processing">this keynote</a>.


<h2>Important Dates</h2>

<ul>
  <li> May 5, 2021: Paper submission (<b>new</b>)</li>
  <li>  May 28, 2021: Notification of acceptance </li>
  <li>  June 7, 2021: Camera-ready papers due </li>
  <li>  August 5-6, 2021: Workshop dates </li>
  </ul>

<h2>Invited Speakers</h2> 

We have an amazing collection of invited talks, many with direct first-hand knowledge of this history, and many insights for the future.

<ol> <li>Past
  <ol>
<li>John Makhoul </li>
<li><a href="#Liberman">Mark Liberman</a></li>
<li><a href="#Voorhees">Ellen Voorhees</a></li>
<li><a href="#Mashey">John Mashey</a></li>
 </ol> </li>
<li>Present
  <ol>
<li>Ming Zhou</li>
<li><a href="#Wu">Hua Wu and Jing Liu</a></li>
<li>Neville Ryant </li>
<li><a href="#MacWhinney">Brian MacWhinney</a> and Saturnino Haider</li>
<li><a href="#Bowman">Samuel Bowman</a></li>
<li><a href="#Kiela">Douwe Kiela</a> </li>
<li>Eunsol Choi</li>
<li><a href="#Sogaard">Anders Søgaard</a></li>
   </ol> </li>
<li> Future
  <ol>
<li>Greg Diamos</li>
<li><a href="#Ferrucci">Dave Ferrucci</a></li>
<li>Ido Dagan </li>
  </ol> </li>
</ol>


<h2>Submissions</h2>

We invite original research papers from a wide range of topics, including
but not limited to:

<ol>
<li>What important technologies and underlying sciences need to be fostered, now and in the future?</li>
<li>In each case, are there existing tasks/benchmarks that move the field in the right direction?</li>
<li>Where are there gaps?</li>
<li>For the gaps, are there initial steps that are accessible, attractive, and cost effective?</li>
<li>How large should a benchmark be?  
  <ol>
<li>How much data do we need to measure significant differences?  </li>
<li>How much data do machines need to obtain good performance?  </li>
<li>How much data do babies need to learn language? </li>
  </ol> </li>
</ol>

</ul>

Submissions to https://www.softconf.com/acl2021/w01_Benchmarking-2021/ should
follow the ACL2021 style, and the <a href="https://www.aclweb.org/adminwiki/index.php?title=ACL_Policies_for_Submission,_Review_and_Citation">ACL submission policy</a>. 
Long papers may consist of up to eight (8) pages of content, plus
unlimited references; short papers may consist of up to four (4) pages of
content.  Final versions will be given one additional page of content so
that reviewers' comments can be taken into account.

<p>
The workshop is scheduled to last for one day either August 5th or 6th. If
you have any questions, contact us at <a href = "mailto: pc-benchmarking-ws-acl2021@googlegroups.com">pc-benchmarking-ws-acl2021@googlegroups.com</a>.

<h2>Workshop Organizers</h2>

<ul>
  <li> Kenneth Church (Baidu USA)</li>
<li> Mark Liberman (University of Pennsylvania)</li>
<li> Valia Kordoni (Humboldt-Universität zu Berlin)</li>
  </ul>
  
<h2>Program Committee</h2>

 
<ul>
<li> Nicoletta Calzolari (Italy) </li>
<li> Kenneth Church (Baidu, USA) </li>
  <li> Christian Federmann (Microsoft Research, USA) </li>
<li> Valia Kordoni (Humboldt, Germany) </li>
<li> Julia Hirshberg (Columbia, USA) </li>
<li> Lori Lamel (LIMSI, France) </li>
<li> Mark Liberman (Penn, USA) </li>
  <li> Phillip Koehn (JHU, USA) </li>
<li>Barbara Plank (IT University of Copenhagen, Denmark)</li>

<li>Preslav Nakov (Qatar Computing Research Institute (QCRI), HBKU)</li>

<li>Anette Frank (University of Heidelberg, Germany)</li>

<li>Roy Bar-Haim (IBM Research - Haifa, Israel)</li>
  </ul>


<h2>Abstracts for Invited Talks</h2>


<h3 id="Bowman">Speaker: Sam Bowman</h3>
<br>
New York University
<br>
<a href="https://cims.nyu.edu/~sbowman/">https://cims.nyu.edu/~sbowman/</a>
<br>
<a href="https://twitter.com/sleepinyourhat">https://twitter.com/sleepinyourhat</a>

<h3>Title: What Will it Take to Fix Benchmarking in Natural Language Understanding?</h3>

Evaluation for many natural language understanding (NLU) tasks is broken: Unreliable and biased systems score so highly on standard benchmarks that there is little room for researchers who develop better systems to demonstrate their improvements. The recent trend to abandon IID benchmarks in favor of adversarially-constructed, out-of-distribution test sets ensures that current models will perform poorly, but ultimately only obscures the abilities that we want our benchmarks to measure. In this position paper, we lay out four criteria that we argue NLU benchmarks should meet. We argue most current benchmarks fail at these criteria, and that adversarial data collection does not meaningfully address the causes of these failures. Instead, restoring a healthy evaluation ecosystem will require significant progress in the design of benchmark datasets, the reliability with which they are annotated, their size, and the ways they handle social bias.

<p>
Bio: Sam Bowman has been on the faculty at NYU since 2016, when he completed PhD with Chris Manning and Chris Potts at Stanford. At NYU, he is a member of the Center for Data Science, the Department of Linguistics, and Courant Institute's Department of Computer Science. His research focuses on data, evaluation techniques, and modeling techniques for sentence and paragraph understanding in natural language processing, and on applications of machine learning to scientific questions in linguistic syntax and semantics. He is the senior organizer behind the GLUE and SuperGLUE benchmark competitions; he organized a twenty-three-person research team at JSALT 2018; and he received a 2015 EMNLP Best Resource Paper Award, a 2019 *SEM Best Paper Award, and a 2017 Google Faculty Research Award.

<h3 id="Ferrucci">Speaker: Dave Ferrucci</h3>
Founder & CEO, <a href="https://ec.ai/">Elemental Cognition</a>
<br>
<a href="mailto:davef@ec.ai">davef@ec.ai</a>
<br>
<a href="https://ec.ai/">ec.ai</a>

<h3>Title: Machine Understanding in Context</h3>

The ability for machines to read, understand and reason about natural
language would dramatically transform the knowledge economy across all
industries. Today’s latest Deep Learning marvels do not understand
what they read to the extent required for rational problem solving and
transparent decision making. And yet we need machines to read,
understand and engage with us at a rational level for us to take
responsibility for their predictions.  A potential problem slowing the
advancement of natural language understanding may be that we are not
ambitiously or rigorously defining what it means to comprehend
language in the first place. Current metrics and tests may be
insufficient to drive the right results. In this talk, I will present
a definition of comprehension and early experimental results that
strongly suggest existing systems are not up to the task. I will also
demonstrate a system architecture and behavior that reflects the sort
of language understanding capabilities we envision would do better to
advance the field of NLU.

<p>  
Bio: Dave Ferrucci is an award-winning Artificial Intelligence
researcher who started and led the IBM Watson team from its inception
through its landmark Jeopardy success in 2011. Dr. Ferrucci’s more
than 25 years in AI and his passion to see computers fluently think,
learn, and communicate inspired him to found Elemental Cognition in
2015. Elemental Cognition is an AI company focused on deep natural
language understanding. It explores methods of learning that result in
explicable models of intelligence and cross-industry applications.  
<p>
Dr. Ferrucci graduated from Rensselaer Polytechnic Institute with a
Ph.D. in Computer Science. He has over 100 patents and
publications. He is an IBM Fellow and has worked at IBM Research and
Bridgewater Associates directing their AI research. He has keynoted at
highly distinguished venues around the world. Dr. Ferrucci serves as a
member of the Connecticut Academy of Science and Engineering and an
Adjunct Professor of Entrepreneurship and Innovation at the Kellogg
School of Management at Northwestern University.  


<h3 id="Kiela">Speaker: Douwe Kiela</h3>
<br>
Facebook AI Research
<br>
<a href="https://douwekiela.github.io/">https://douwekiela.github.io/</a>
<br>
@douwekiela on Twitter

<h4>Title: Rethinking Benchmarking in AI</h4>

The current benchmarking paradigm in AI has many issues: benchmarks saturate quickly, are susceptible to overfitting, contain exploitable annotator artifacts, have unclear or imperfect evaluation metrics, and do not necessarily measure what we really care about. I will talk about our work in trying to rethink the way we do benchmarking in AI, specifically in natural language processing, focusing mostly on the Dynabench platform.

<p>

Bio: Douwe Kiela is a Research Scientist at Facebook AI Research, working on natural language processing and multimodal reasoning and understanding. His work has mainly been focused on representation learning, grounded language learning and multi-agent communication. Recently, he has become interested in improving the way we evaluate AI systems.

<h3 id="Liberman">Speaker: Mark Liberman</h3>

<h4>Title: Benchmarking as a Method for Long-Term Research Management: The Common Task Method</h4>

Over the course of half a century, DARPA's Human Language Technology program created capabilities such as speech recognition, machine translation, and text understanding, turning them from science fiction fantasies to everyday practical fact. This sustained success was based on the development of the Common Task Method, which allowed decades of incremental progress in advance of commercial viability. I'll describe the origin and (sometimes counter-intuitive) progress of this method, distinguish it from other uses of benchmarking, and speculate about its future.
<p>
Bio: Mark Liberman is the Christopher H. Browne Professor of Linguistics at the University of Pennsylvania, with positions in the department of computer science and in the psychology graduate group. He is also founder and director of the Linguistic Data Consortium. Before coming to the University of Pennsylvania, he was head of the linguistics research department at AT&T Bell Laboratories.


<h3 id="MacWhinney">Speaker: Brian MacWhinney</h3>
<br>
Language Technologies and Modern Languages, CMU

<p>
Diagnosis or early detectioin of the onset of dementia is important
for interventions and planning for life-style changes.  Ideally, we
would like to achieve accurate diagnosis based on samples of
naturalistic language production, as well as samples ellicited using
some standard formats, such as narrative, script reading, or picture
description. Currently, research in this area relies primarily on the
Pitt Corpus in DementiaBank which includes cookie theft narratives
from 104 controls, 208 persons with dementia, and 85 persons with
unknown diagnosis. These data were used in the ADReSS challenge for
INTERSPEECH2020 and will be used in a new challenge for 2021.  The
previous challenge used hand-created transcripts.  The new challenge
focuses on a pipeline that can be applied automatically, using ASR and
NLP methods. The four major gaps in the current data set are: 1) we
need fuller ancillariy data on cognitive and medical status, 2) we
need longitudinal data on progression, 3) we need more data across
language task and interaction types, and 4) ideally, we would like to
have data recorded in the home with voice assistant technology.
Currently, challenge participants are committed to open sharing of
algorithms, but we need more sharing of primary language data,
including data outside of English.

<p>
Bio: Brian MacWhinney is Teresa Heinz Professor of Psychology,
Computational Linguistics, and Modern Languages at Carnegie Mellon
University. His Unified Competition Model analyzes first and second
language learning as aspects of a single basic system. He has
developed a series of 13 TalkBank open access online databases for the
study of language learning, multilingualism, and language
disorders. The databases for language disorders include AphasiaBank,
ASDBank, DementiaBank, FluencyBank, RHDBank, and TBIBank. These
databases provide transcriptions of spoken language linked to audio
and video media, along with programs for analysis and linguistic
profiling. His other research topics include methods for online
learning of second language vocabulary and grammar, neural network
modeling of lexical development, fMRI studies of children with focal
brain lesions, ERP studies of between-language competition, and the
role of embodied perspectival imagery in sentence processing.

<h3 id="Mashey">Speaker: John Mashey</h3>
<br>
<a href="https://en.wikipedia.org/wiki/John_Mashey">https://en.wikipedia.org/wiki/John_Mashey</a>
<br>
<a href="https://www.spec.org/benchmarks.html">https://www.spec.org/benchmarks.html</a>
<br>
<a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.325.7027&rep=rep1&type=pdf"> War of the Benchmark Means: Time for a Truce</a>, ACM SIGARCH, 2004.
<br>
<a href="https://ieeexplore.ieee.org/document/1525995">Summarizing Performance is No Mean Feat</a>, IEEE 2005
<br>
<a href="https://bits.blogs.nytimes.com/2013/02/01/the-origins-of-big-data-an-etymological-detective-story">https://bits.blogs.nytimes.com/2013/02/01/the-origins-of-big-data-an-etymological-detective-story</a>
<br>
Twitter:@johnmashey

<h4>Title: Lessons from SPEC</h4>
 

In the 1980s, amidst fierce competition among new microprocessor architectures, CPU benchmarking was in poor condition.
Many commonly-used benchmarks were  small synthetic benchmarks like Whetstone and Dhrystone that poorly-matched realistic programs.
Companies sometimes outright cheated by special-casing compilers to recognize major benchmarks.
Some vendors honestly reported results from realistic benchmarks, but even when running the same programs, often used different inputs,
so that potential customers could not easily make direct comparisons. Many customers did not trust performance claims.

<p> 
The talk reviews the odd way SPEC got started in 1988, initially by MIPS, Apollo, Hewlett-Packard and Sun, later joined by many others,
then covers the ground rules that evolved to let fierce competitors work together successfully to produce benchmarks that became industry standards and
exemplars of good methodologies for selecting benchmarks, validating results, reporting them carefully and deciding when they had to be retired as obsolete for one reason or another.

<p>
SPEC of course is still active, 30+ years later.
The talk reviews lessons learned about high-stakes benchmarking, evolution of benchmark suites over time, competitor social issues, credibility issues when people think the foxes are guarding the henhouse,
as we were asked by a member of the press.
From the beginning, SPEC reported performance on a set of benchmarks as a set of ratios versus a base system, so that people could find benchmarks they thought relevant to their own and ignore the others.
Many arguments had occurred over summary means, but as had been done in some performance reports, SPEC correctly used the Geometric Mean, but without really delving into the underlying statistics,
which only happened in 2004.

<p>
A set of benchmark ratios can be viewed as a sample (representative if selected by experts) from a large population of programs.
In practice, many sets of benchmark ratios are well-fit by the lognormal distribution, whose mean is the Geometric Mean, but also allows computation of a (Multiplicative) Standard Deviation, Confidence Intervals, etc.
The talk briefly reviews the relevant, simple statistics and the rationale for them.

<p>
Bio: John Mashey is a semi-retired computer scientist/corporate executive at Bell Labs, Convergent Technologies, MIPS Computer Systems and Silicon Graphics,
where he is was originator of the phrase “Big Data” (according to NY Times).
He later consulted for venture capitalists, advised startups and occasionally consulted for companies like Nvidia. He is a 20-year Trustee at the Computer History Museum.
He was one of the 4 cofounders of the SPEC benchmarking group in 1988 and was asked in 2018 to advise the MLperf benchmarking group on relevant statistics.


<h3 id="Voorhees">Speaker: Ellen Voorhees</h3>
<br><a href="https://trec.nist.gov">National Institute of Standards and Technology</a>
<br><a href="https://www.nist.gov/people/ellen-m-voorhees">https://www.nist.gov/people/ellen-m-voorhees</a>

<p>
Coopetitions are activities in which competitors cooperate for a common good. Community evaluations such as the Text REtrieval Conference (TREC) are prototypical examples of coopetitions in information retrieval (IR) and have now been a part of the field for thirty years. This longevity and the proliferation of shared evaluation tasks suggest that, indeed, the net impact of community evaluations is positive.  But what are these benefits, and what are the attendant costs?

This talk will use TREC tracks as case studies to explore the benefits and disadvantages of different evaluation task designs. Coopetitions can improve state-of-the-art effectiveness for a retrieval task by establishing a research cohort and constructing the infrastructure---including problem definition, test collections, scoring metrics, and research methodology---necessary to make progress on the task. They can also facilitate technology transfer and amortize the infrastructure costs. The primary danger of coopetitions is for an entire research community to overfit to some peculiarity of the evaluation task. This risk can be minimized by building multiple test sets and regularly updating the evaluation task.]

<p> Bio: Ellen Voorhees is a Senior Research Scientist at the US National Institute of Standards and Technology (NIST).  Her primary responsibility at NIST is to manage the Text REtrieval Conference (TREC) project, a project that develops the infrastructure required for large-scale evaluation of search engines and other information access technology.  Voorhees' research focuses on developing and validating appropriate evaluation schemes to measure system effectiveness for diverse user tasks.
<p>
Voorhees is a fellow of the ACM and an inaugural member of the ACM SIGIR Academy.   She has published numerous articles on information retrieval techniques and evaluation methodologies and serves on the review boards of several journals and conferences.


<h3 id=Sogaard>Speaker: Anders Søgaard</h3>
University of Copenhagen
<br><a href="https://anderssoegaard.github.io/">https://anderssoegaard.github.io/</a>

<h4>Title: Ways to Make Your Data More Relevant</h4>


<h3 id="Wu">Speakers: Hua Wu and Jing Liu</h3>
<br>
Baidu
<br>
<a href="https://wuhuanlp.github.io/">Hua Wu</a>
<br>
<a href="https://www.machinereading.ai/">Jing Liu</a>

<h4>Title: Benchmarks: An Industry Perspective</h4>

In recent years, the researchers from academia created large-scale
datasets mainly in a crowdsourcing way, that accelerate the
development of NLP technology. However, these datasets might present
different distributions and different challenges from the ones in
real-world applications. In this talk, we will introduce our efforts
on building NLP benchmarks from an industry perspective. Specifically,
we will describe our released datasets on the tasks including question
answering, dialogue and simultaneous translation that were created to
tackle with the problems in industrial applications. We will present
the challenges of these datasets and show how these datasets drive the
advancements of NLP technologies. Additionally, we will talk about
LUGE, which is an Open-Source Project of Chinese NLP benchmarks. LUGE
aims to evaluate NLP models in terms of robustness and adaptability
across multiple tasks and multiple domains, which are very crucial for
their success in industrial applications.
 
<p>
Bios:

Hua Wu is the chair of Baidu tech committee and tech leader of Baidu NLP. Before that, she worked for Toshiba (China) R&D center and Microsoft Research Asia. She obtained her Ph.D. degree from Institute of Automation, Chinese Academy of Science in 2001. Her research interests span a wide range of topics including machine translation, dialogue systems, knowledge graph, etc. She was the Program Co-Chair of ACL 2014 and AACL 2020 (Asia-Pacific Chapter of ACL).
<p>
Jing Liu is a principal architect and a tech leader of deep question answering team at Baidu NLP since 2017. Before that, he was a researcher at Microsoft Research Asia (MSRA). He obtained Ph.D. degree in computer science from Harbin Institute of Technology (HIT) in 2014. He is interested broadly in natural language processing and information retrieval, with a particular focus on building robust end-to-end question answering system. He published over 30 research papers in prestigious conferences including ACL, EMNLP, NAACL, SIGIR, WSDM, CIKM, etc. He served as an Area Chair in ACL 2021.

 
</body>
</html>
