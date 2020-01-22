# Construct a simple multimodal distribution

I have used MATLAB to construct a simple multimodal distribution for One-dimension. This can easily be extended to multiple dimensions. Beauty of this simple (or I should call simplest) code is that it does not require any fancy package such as mvnrnd or gmdistribution that people use in their work. Let me know if you are finding difficulties in extending this to multiple dimension case.

To use this:

Open your MATLAB environment (command window)

> help multimodalDistro
> 
>   ### P = multimodalDistro(N,k) ###
>   
>   Inputs: N: Locations, k: Proportion of spikes
> 
>   Output: P: A multimodal distribution
>   
> P = multimodalDistro(100,0.10); plot(P); xlabel('x'); ylabel('P(x)');

![A Sample distribution for above command](https://github.com/tirtharajdash/multimodalGaussianDistro/blob/master/sample.jpg)
