# cse641-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSE641 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cse641-deep-learning-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127105&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE641  Assignment  2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Instructions &amp; Guidelines

• This coding assignment revolves around developing custom deep convolutional network and manually training it. Additional instructions for each question are provided accordingly.

• No extensions will be granted for this assignment under any circumstances.

• You have to submit only changerollno.py. Rename it according to your rollnumber. Ensure that you follow the naming convention as rollnoA2.py. Any submissions without adhering to the naming convention, having multiple files in submission including .ipynb files, and any additional files will not be evaluated.

For instance, if your roll number is 1234567 / MT34567, the file name should be 1234567A2.py / MT34567A2.py.

Coding Guidelines

• Follow Readme.txt to setup the environment and start coding.

• You will receive a pipeline for training the architectures. Within the pipeline folder, locate a file named changerollno.py. Your task is to edit only this specific file .

• Minimum accuracy you have to achieve is 45% for each question to be eligible to get evaluated.

All these networks are easily trainable on Google Colaboratory

Figure 1: Block diagram for different architectures.

Figure 1 illustrates different blocks from various deep learning architectures. Your task is to implement these blocks and train them using two datasets: CIFAR-10 and SpeechCommand V0.02. Follow the provided instructions for each question. Only use PyTorch’s dataset library torchvision.datasets for image data and torchaudio.datasets for audio data when downloading the datasets.

1

1. ResNet

In Figure.1, (A) represents a single ResNet block. Here, (3×3 Conv(1D/2D)) denotes a single convolution layer with a filter size of 3×3 for 2D data and 1×3 for 1D data, (Batch norm(1D/2D)) represents a single Batch normalization layer for 1D or 2D data, and (ReLU) represents the rectified linear unit activation function. Your task is to create a network comprising 18 such blocks and train it on both datasets. For the image dataset, use 2D Convolutions and Batch normalization, while for the audio dataset, use 1D Convolutions and Batch normalization. Utilize Cross-Entropy as the loss function and Adam as the optimizer with default parameters specified in the script.

2. VGG

In Figure.1, (B) outlines the modified VGG architecture. After each pooling layer, the number of channels is reduced by 35%, and the kernel size is increased by 25% (with ceil rounding for float calculations). Here, (Conv n-m) denotes the nth block and mth layer within that block. Your task is to create a VGG network and train it on both image and audio datasets using the specified loss function and optimizer from the previous question.

3. Inception

In Figure.1, (C) illustrates the configuration of a single inception block, where (n×n (CNA)) denotes a sequence of convolution, batch normalization, and ReLU activation with an n×n convolution filter. Your task is to construct a modified inception network comprising 4 such blocks and train it on both audio and image data, following similar configurations as in the previous two questions.

4. Design a custom network using the following combination of blocks and follow the channel reduction and kernel size increase as in VGG. Train it on both image and audio datasets, adhering to configurations similar to those in the previous questions.

• Network Architecture

(a) Input Layer

(b) Residual Block × 2

(c) Inception Block × 2

(d) Residual Block × 1

(e) Inception Block × 1

(f) Residual Block × 1

(g) Inception Block × 1

(h) Residual Block × 1

(i) Inception Block × 1

(j) Classification Network

• A classification network here refers to a combination of either nn.Linear or nn.Conv1d, nn.Conv2d layers that produce logits for the classification task.

2
