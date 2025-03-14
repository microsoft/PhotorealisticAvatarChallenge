# Photorealistic Avatar Challenge -CVPR 2025
[[challenge website](https://www.microsoft.com/en-us/research/academic-program/photorealistic-avatar-challenge-cvpr-2025/)]

The Photorealistic Avatar challenge testset consists of videos from different people and is divided into two parts:
- The 1st part is the initial set provided during the start of the challenge. This has videos from 5 different persons.
- The 2nd part is another set of videos from 10 different persons, provided 1 week before the challenge submissions.

The initial set of URLs are found in the file [InitialSet.txt](https://github.com/microsoft/PhotorealisticAvatarChallenge/blob/main/InitialSet.txt) and the final set of URLs in the file [FinalSet.txt](https://github.com/microsoft/PhotorealisticAvatarChallenge/blob/main/FinalSet.txt)

## Download

1. Clone the repository:

```bash
git clone https://github.com/microsoft/PhotorealisticAvatarChallenge.git
cd PhotorealisticAvatarChallenge
```

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Download the txt file with the list of URLs from [1st part](InitialSet.txt?raw=true) or 2nd part of testset.

4. Change LOCAL_PATH to a path in your file system and run the following command. Replace file_list.txt with the list of files (e.g. InitialSet.txt) you are interested in:

```bash
python downloader.py --list-of-files file_list.txt --local-path LOCAL_PATH
```

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


## Dataset license

This dataset is released under the [Community Data License Agreement – Permissive, Version 2.0 - CDLA](https://cdla.dev/permissive-2-0/). See the [LICENSE-DATA](LICENSE-DATA) file for more details.


## Code license

MIT License

Copyright (c) Microsoft Corporation.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE



## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
