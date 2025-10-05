# my-new-project
Building AI course  project
[README.md](https://github.com/user-attachments/files/22711013/README.md)
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Painting with AI

Final project for the Building AI course

## Summary

This project explores how artificial intelligence can generate simple art pieces from human prompts and emotions. The idea is to let users describe a feeling or a short scene, and then the AI tries to "paint" that mood using color patterns and shapes. It’s about mixing creativity with code.

## Background

Many people want to express emotions through art but don’t have the skills or confidence to paint. AI tools can help turn their imagination into something visual.  
My motivation came from the frustration of staring at a blank canvas and not knowing how to start — what if an algorithm could help?  

This project tries to solve:
* Lack of artistic confidence
* Limited access to creative tools
* The gap between human emotion and digital art

## How is it used?

The user types a short description, for example *"a lonely night near the sea"* or *"happy morning in spring"*.  
The AI model converts the text into a color palette and abstract image using a simple neural network and a dataset of emotional color mappings.  

It could be used by:
* digital artists for inspiration,
* people learning about AI art generation,
* or anyone who just wants to play with creative technology.

Images will make your README look nice!  
Once you upload an image to your repository, you can link it like this:  
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:  
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
    moods = ['happy', 'sad', 'calm', 'angry', 'nostalgic']
    colors = {
        'happy': 'yellow',
        'sad': 'blue',
        'calm': 'green',
        'angry': 'red',
        'nostalgic': 'sepia'
    }

    for mood in moods:
        print(f"For mood '{mood}', I would paint with {colors[mood]} shades.")

main()
```

## Data sources and AI methods

The data mainly comes from small open-source datasets of paintings and emotional color palettes.  
I also used some self-collected examples — asking friends to describe how certain moods “look” in colors.  

Methods used:
* Text preprocessing with TF-IDF
* Basic feedforward neural network
* Image generation with color mapping  

[EmoColor dataset](https://github.com/yourlinkhere) is one of the references used.

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

The AI doesn’t really *understand* emotions — it just imitates patterns found in the training data.  
It might sometimes produce weird or unrelated images. Also, art is subjective, so evaluating “success” is difficult.  
Ethical point: it’s important not to train on copyrighted artworks without permission.

## What next?

I’d like to improve the text-to-image part, maybe use a small diffusion model.  
It could also let users mix multiple emotions — like “happy but lonely”.  
To move forward, I’d need better GPU resources, more labeled data, and probably a friend who’s good at color theory.  

## Acknowledgments

* Inspired by AI art tools like DeepDream and DALL·E mini  
* Built using public examples from the Building AI course  
* Some ideas for emotional color mapping came from research on color psychology  
* [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
