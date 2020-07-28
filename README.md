# Malicious-Web-Detection-with-1D-CNN
## Description:
I built a model to detect malicious web detection with 1D-CNN. I explored the data first, then do tokenization on the these urls, padding them to same length. Next I encoded the character variables(subdomain, domain, suffix domains and label) to numeric variables. Afterwards, the1D-CNN model was trained with 4 inputs: the data from tokenizated urls, encoded subdomains, domains and suffix domains. I also tried to use early stopping technique later, which gave better performance.
## Results:
Refer to pic1.png in 'pics' file
