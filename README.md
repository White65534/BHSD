# BHSD


Intracranial hemorrhage (ICH) is a pathological condition characterized by bleeding inside the skull or brain, which can be attributed to various factors. 
Identifying, localizing and quantifying ICH has important clinical implications, in a bleed-dependent manner. 
While deep learning techniques are widely used in medical image segmentation and have been applied to the ICH segmentation task, existing public ICH datasets do not support the multi-class segmentation problem. 
To address this, we develop the Brain Hemorrhage Segmentation Dataset (BHSD), which provides a 3D multi-class ICH dataset containing 192 volumes with pixel-level annotations and 2200 volumes with slice-level annotations across five categories of ICH. 
To demonstrate the utility of the dataset, we formulate a series of supervised and semi-supervised ICH segmentation tasks. 
We provide experimental results with state-of-the-art models as reference benchmarks for further model developments and evaluations on this dataset. 




 


![BHSD](brains.png)


 

## 📚 Datasets 
- deep-dive into the datasets used in the paper! [Click here for a dive into dataset strategies](docs/DATASETS.md)

## 💼 Commercial Use-Cases

Med Palm has thousands of potential use cases the 3 below are simple, for more detailed applications check out my new blog article on MedPalm's use in the real world. [Click here to learn more](https://medium.com/@kyeg/how-medpalm-is-revolutionizing-medicine-62eef979f0e5)

- **Clinical Diagnostics**: Combining medical imaging, patient tales 📖, and genes, we're aiming for top-notch diagnostic solutions.
  
- **Healthcare Research**: Dive deep into diverse datasets and discover something new with Med-PaLM by your side! 🤿
  
- **Telemedicine**: Quick, reliable, and remote! 🌍 Med-PaLM's here to revolutionize telehealth.

# Contributing to Med Palm 🤖🌟

First off, big high fives 🙌 and thank you for considering a contribution to Med Palm! Your help and enthusiasm can truly elevate this project. Whether you're fixing bugs 🐛, adding features 🎁, or just providing feedback, every bit matters! Here's a step-by-step guide to make your contribution journey smooth:

## 1. Set the Stage 🎬

**Fork the Repository:** Before you dive in, create a fork of the Med Palm repository. This gives you your own workspace where you can make changes without affecting the main project.

1. Go to the top right corner of the Med Palm repo.
2. Click on the "Fork" button. 

Boom! You now have a copy on your GitHub account.

## 2. Clone & Set Up 🚀

**Clone Your Fork:** 
```bash
git clone https://github.com/kyegomez/Med-PaLM.git
cd Med-PaLM
```

**Connect with the Main Repo:** To fetch updates from the main Med Palm repository, set it up as a remote:
```bash
git remote add upstream https://github.com/kyegomez/Med-PaLM.git
```

## 3. Make Your Magic ✨

Create a new branch for your feature, bugfix, or whatever you're looking to contribute:
```bash
git checkout -b feature/my-awesome-feature
```

Now, dive into the code and sprinkle your magic!

## 4. Stay Updated 🔄

While you're working, the main Med Palm repository might have updates. Keep your local copy in sync:

```bash
git fetch upstream
git merge upstream/main
```

## 5. Share Your Brilliance 🎁

Once you've made your changes:

1. **Stage & Commit:**
   ```bash
   git add .
   git commit -m "Add my awesome feature"
   ```

2. **Push to Your Fork:**
   ```bash
   git push origin feature/my-awesome-feature
   ```

3. **Create a Pull Request:** Head back to your fork on GitHub, and you'll see a "New Pull Request" button. Click on it!

## 6. The Review Dance 💃🕺

Once your PR is submitted, our team will review it. They might have questions or feedback. Stay engaged, discuss, and make any needed changes. Collaboration is key! 🤝

## 7. Celebrate 🎉

After review and any necessary tweaks, your contribution will be merged. Pat yourself on the back and celebrate! 🎊

## 8. Spread the Word 📢

Share about your contribution with your network. The more the merrier! Plus, it feels good to show off a bit, right? 😉

Remember, every contribution, no matter how small or large, is valued and appreciated. It's the collective effort that makes open-source so vibrant and impactful. Thanks for being a part of the Med Palm adventure! 🌟🚀

----

## License

Med-PaLM's is under the MIT license. Check out the details [here](LICENSE.md).

## Citation

Tao Tu, Shekoofeh Azizi, Danny Driess, Mike Schaekermann, Mohamed Amin, Pi-Chuan Chang, Andrew Carroll, Chuck Lau, Ryutaro Tanno, Ira Ktena, Basil Mustafa, Aakanksha Chowdhery, Yun Liu, Simon Kornblith, David Fleet, Philip Mansfield, Sushant Prakash, Renee Wong, Sunny Virmani, Christopher Semturs, S Sara Mahdavi, Bradley Green, Ewa Dominowska, Blaise Aguera y Arcas, Joelle Barral, Dale Webster, Greg S. Corrado, Yossi Matias, Karan Singhal, Pete Florence, Alan Karthikesalingam, Vivek Natarajan. "Towards Generalist Biomedical AI." arXiv:2307.14334 [cs.CL], July 26, 2023.
