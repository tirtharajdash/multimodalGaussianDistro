# Construct a simple multimodal distribution

I have used MATLAB to construct a simple multimodal distribution for One-dimension. This can easily be extended to multiple dimensions. 

To use this:

Open your MATLAB environment (command window)

> help multimodalDistro
>   ### P = multimodalDistro(N,k) ###
>   Inputs: N: Locations, k: Proportion of spikes
>   Output: P: A multimodal distribution
  
> P = multimodalDistro(100,0.10); plot(P); xlabel('x'); ylabel('P(x)');

