# Programming Languages and Art
Keira Ryan

keiryan@chapman.edu


## Large Language Model Literature Review

The following review is an exploration of how programming languages can be utilized in art, conducted through conversation with ChatGPT 4.

**Topics Explored**
1. Question 1 : How can artists use programming languages as a tool in their work?
2. Question 2 : What do experts have to say on whether works created using AI are art or not?
3. Question 3 : How do programming lanugages analyze art and identify/emulate style?

## Question 1: How can artists use programming languages as a tool in their work?
With the advancement of technology, programming languages have become indispensable tools in contemporary art, allowing artists to create works that venture beyond the constraints of traditional media. From generative visual art to interactive installations and algorithmic music, programming opens new creative avenues that inspire a blending of aesthetics, technology, and innovation.

### Generative Art
Generative art refers to works formed by algorithms that follow a set of rules, rules defined by the artist using a programming language. Depending on the artist's direction, the output can be visual, auditory, or even sculptural. Artists often use languages like **Processing**, **p5.js**, or **Python** to manipulate artwork through dynamic parameters.

### Processing

Processing, a language developed by Casey Reas and Ben Fry, whose work is cited below, has been instrumental in making programming accessible to artists. Designed as an entry-level tool for non-programmers, Processing is widely used to create visually rich and complex generative art. It enables artists to define algorithms that control aspects such as form, color, and movement, creating outcomes that can evolve over time.

Scholars like McCormack (see References) emphasize the role of the artist as a systems designer in generative art, where the creation process involves setting up rules rather than manually shaping each element of the artwork. Similar to a sport or game, this method allows for infinite variations, making the work dynamic and often interactive. As McCormack states, "the generative process, once initiated, can produce outcomes that the artist may not have predicted, blending human creativity with machine autonomy".


### p5.js

p5.js is a JavaScript library based on Processing, extending the same principles into the web environment. Artists can create interactive web-based artworks using simple code that runs in any browser. P5.js fosters a culture of open-source creation, encouraging collaboration and remixing in the digital art community. By leveraging the web as a medium, artists can create interactive pieces that respond to user input, blurring the boundaries between artist and audience. The existence of a buildable, collaborative hub is integral to the accessiblity of the practice.


### Interdisciplinarity

Popular programming languages like Python and JavaScript, often paired with libraries like p5.js**, have enabled artists to create browser-based artworks that are both interactive and visually engaging. For example, Lozano-Hemmer’s installations often use code to monitor real-time human interaction, allowing viewers to manipulate visual projections and soundscapes. His works exemplify how programming can create relational architectures, where the audience plays an active role in shaping the artwork. Interactive programming creates a dynamic relationship between the art and the audience, enhancing the immersive experience and making each interaction unique.



Though on the rise, generative art poses a challenge to traditional notions of the artist as the sole creator. Instead, it positions the artist as a co-creator with the machine, exploring how randomness and rule-based systems contribute to the final outcome of a work.

## Question 2: What do experts have to say on whether works created using AI are art or not?
The question of whether art created using artificial intelligence is truly "art" has sparked debate among scholars, critics, and artists. The discussion largely revolves around what defines creativity, authorship, and the role of the artist in the creation process.

### AI as a Tool for Expression

One supported argument is that AI is merely a tool—like a paintbrush or a camera—that artists use to explore new creative possibilities. In this view, the artistic intent and creativity still reside with the human artist who defines the parameters, selects the dataset, and curates the final output. Below are researchers who have focused on this line of thinking, both of whose work is cited in the References section:

- **Margaret Boden**, a cognitive scientist specializing in artificial intelligence and creativity, suggests that AI can be used to extend human creativity but cannot truly originate creative ideas in the way that humans do. According to Boden, "creativity requires intentionality, emotional engagement, and subjective experience—qualities that machines lack". She emphasizes that AI-generated art is a result of human-AI collaboration rather than machine autonomy, with the human artist playing the key role of framing the creative problem and interpreting the result, the data also being pulled from human-made resources.
- **Ahmed Elgammal**, director of the Art and AI Lab at Rutgers University, shares a similar view. In his research, he argues that AI can push the boundaries of art by introducing new styles and techniques, but the human artist is always responsible for guiding the creative process. He compares AI-generated art to using other technologies like Photoshop or CAD software, which also require human input and decision-making. Elgammal’s AI-generated art project, AICAN, is an example where AI algorithms were trained on a large dataset of classical and modern art to generate new works, but the final output still required human selection and curation.

### Criticism of AI as Art
Critics of AI-generated art often question whether machines can genuinely be creative, given that they lack consciousness and intentionality—qualities traditionally associated with artistic creation. 

- **Garry Kasparov**, the former world chess champion and a vocal commentator on AI, expresses skepticism about AI’s capacity for genuine creativity. He argues that AI can only mimic creativity based on the data it is trained on, but it cannot generate truly original ideas. According to Kasparov, AI lacks the ability to experience the world, form emotional connections, or understand the deeper cultural and philosophical implications of art. For him, AI art is merely the result of statistical patterns, rather than true creative thought.

### Who Owns AI Art?

The question of when AI-generated work becomes the property of others—such as the programmer, the dataset provider, or even the public—touches on legal and ethical issues surrounding authorship and ownership.

- According to Lawrence Lessig, a legal scholar known for his work on intellectual property, AI-generated art poses significant challenges to current copyright laws. Lessig argues that when the machine plays a significant role in generating the creative output, we must rethink what it means to be an author. He suggests that copyright laws may need to evolve to recognize shared authorship between the human and the machine, or even introduce new legal frameworks.

## Question 3 : How do programming lanugages analyze art and identify/emulate style?
Programming languages, particularly when integrated with machine learning and artificial intelligence, play a significant role in analyzing and identifying art styles. These techniques leverage various methods, such as convolutional neural networks (CNNs), deep learning, and computer vision algorithms, to recognize patterns, features, and stylistic elements in visual artworks.

## Convolutional Neural Networks and Deep Learning
Convolutional Neural Networks (CNNs) are one of the most common techniques used for image classification and style recognition in artworks. These neural networks are trained on large datasets of labeled art images to learn specific features associated with different styles, such as color palettes, brushstrokes, and compositional patterns. The following is a high-level breakdown of the process: 

- A CNN processes an image through multiple layers, where each layer detects different features like edges, textures, or shapes.
- Deeper layers combine these features to recognize more complex patterns, such as faces, objects, or, in the case of art, specific artistic elements.
- For style classification, CNNs can be trained to distinguish between art movements like Impressionism, Baroque, etc., based on visual patterns learned during training.

### Style Transfer
Style transfer is a popular AI technique that uses neural networks to apply the style of one image, usually a famous painting, to the content of another image. While this technique is often used for entertainment or creative purposes, it also provides insights into how AI understands and distinguishes different artistic styles. The following is a high-level breakdown of the process:

- A pre-trained neural network extracts content from one image and style features from the other
- Style features include color patterns, texture details, and brushstroke styles, which are then recombined to produce an image that has the content of the first image but the style of the other.

### Cultural and Historical Context
In addition to analyzing visual features, programming languages are now being used to assess the cultural and historical context of artworks. By analyzing metadata, such as the period in which the artwork was created, the artist's background, and influences from specific historical events, AI can enhance its understanding of art styles and movements. The following is a high-level breakdown of the process:

- Natural Language Processing (NLP) techniques are used to analyze art-related texts, such as exhibition catalogs, critiques, and academic papers.
- These tools help AI models to understand art history in a broader context, connecting visual styles with cultural, political, and social influences.

## Conclusion
All in all, art and technology have a long history of engagement. As with all fields, the rise of artificial intelligence has raised questions as to originality and agency. However, reminiscent discussions such as those concerning digital art and generative art tools exist and set precedence for future conversation. By referencing previous standards of creativity in the lens of new technologies, creatives can make informed decisions when experimenting with new processes. 

## References
Boden, Margaret A. AI: Its nature and future. Oxford University Press, 2016. https://books.google.com/books?hl=en&lr=&id=yDQTDAAAQBAJ&oi=fnd&pg=PP1&dq=AI:+Its+nature+and+future&ots=T2fn3A64Ob&sig=woI-paE0Adh4_WuZwgpyfwOaxpc#v=onepage&q=AI%3A%20Its%20nature%20and%20future&f=false 

De Cremer, David, and Garry Kasparov. "AI should augment human intelligence, not replace it." Harvard Business Review 18.1 (2021). https://www.daviddecremer.com/wp-content/uploads/HBR2021_AI-Should-Augment-Human-Intelligence-Not-Replace-It.pdf 

Elgammal, Ahmed, et al. "CAN: Creative Adversarial Networks Generating “Art” by Learning About Styles and Deviating from Style Norms." arXiv preprint arXiv:1706.07068 (2017). https://arxiv.org/abs/1706.07068 

Galanter, Philip. "Generative art theory." A companion to digital art (2016): 146-180. https://onlinelibrary.wiley.com/doi/abs/10.1002/9781118475249.ch5 

Gatys, L. A., Ecker, A. S., & Bethge, M. "A Neural Algorithm of Artistic Style." *ArXiv Preprint*. (2015). https://arxiv.org/abs/1508.06576

Karayev, S., Hertzmann, A., & Winnemoeller, H. "Recognizing Image Style." *European Conference on Computer Vision* (ECCV). (2014). https://arxiv.org/abs/1311.3715

Lawrence, Lessig. "Making Art and Commerce Thrive In The Hybrid Economy." (2008). http://dspace.kottakkalfarookcollege.edu.in:8001/jspui/bitstream/123456789/147/1/Remix-o.pdf 

McCormack, Jon, Toby Gifford, and Patrick Hutchings. "Autonomy, authenticity, authorship and intention in computer generated art." International conference on computational intelligence in music, sound, art and design (part of EvoStar). Cham: Springer International Publishing, 2019. https://arxiv.org/abs/1903.02166 

Reas, Casey. Processing: A Programming Handbook for Visual Designers and Artists. The MIT Press, 2007. https://books.google.com/books?hl=en&lr=&id=tqW75bfJkxIC&oi=fnd&pg=PR19&dq=reas+processing:+a+programming+handbook&ots=SpWXUIQKV7&sig=wcWBpgfXBMarf3q2Z5OEPMgdac0#v=onepage&q=reas%20processing%3A%20a%20programming%20handbook&f=false 

Saleh, B., & Elgammal, A. "Large-scale Classification of Fine-Art Paintings: Learning The Right Metric on The Right Feature." *ArXiv Preprint*. (2015). https://arxiv.org/abs/1505.00855







