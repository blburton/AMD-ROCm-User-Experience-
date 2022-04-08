# Contributor's Guide Template
### 1. Contributor's Guide ( library name )
#### 1.1. Pull-request Guidelines 
ROCm libraries follows the model of [GitHub pull-requests](https://help.github.com/articles/using-pull-requests/).

Pull requests should:

- Target the develop branch for integration.

- Ensure code builds successfully.

- Do not break existing test cases.

- New functionality will only be merged with new unit tests.

- New unit tests should integrate within the existing googletest framework.

- Tests must have good code coverage.

- Code must also have benchmark tests, and performance must approach the compute bound limit or memory bound limit.
#### 1.2. Style Guide

Follow the [CPP Core guidelines](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md). 

##### 1.2.1. Interface
Include information regarding the API.

##### 1.2.2. Philosophy
Include a list of the philosophical rules and link directly to the Cpp Core Guidelines page. 
Follow example: 

[P.1.](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#Rp-direct): Express ideas directly in code

##### 1.2.3. Implementation
Include a list of the source files, link directly to the Cpp Core Guidelines page. Code is to be in greyscale.

##### 1.2.4. Format
C and C++ code is formatted using `clang-format`.

#### 1.3. Coding Guidelines
In this section include guidelines and information developers will by required to follow.

#### 1.4. Static Code Analysis
In this section include the tools and commands used to rebug and run the program. 

Ensure code blocks are in greyscale 

### 2. Acknowledgement 
In this section list the contributors and where they're from. If possible include specific of contribution.

Example:

"AMD would like to thank the following people for their code contributions to (insert library/tool/etc):
    John Jacobs of the University of Pennsylvannia"

### 3. Disclaimer

The information presented in this document is for informational purposes only and may contain technical inaccuracies, omissions, and typographical errors. The information contained herein is subject to change and may be rendered inaccurate for many reasons, including but not limited to product and roadmap changes, component and motherboard version changes, new model and/or product releases, product differences between differing manufacturers, software changes, BIOS flashes, firmware upgrades, or the like. Any computer system has risks of security vulnerabilities that cannot be completely prevented or mitigated. AMD assumes no obligation to update or otherwise correct or revise this information. However, AMD reserves the right to revise this information and to make changes from time to time to the content hereof without obligation of AMD to notify any person of such revisions or changes. THIS INFORMATION IS PROVIDED ‘AS IS.” AMD MAKES NO REPRESENTATIONS OR WARRANTIES WITH RESPECT TO THE CONTENTS HEREOF AND ASSUMES NO RESPONSIBILITY FOR ANY INACCURACIES, ERRORS, OR OMISSIONS THAT MAY APPEAR IN THIS INFORMATION. AMD SPECIFICALLY DISCLAIMS ANY IMPLIED WARRANTIES OF NON-INFRINGEMENT, MERCHANTABILITY, OR FITNESS FOR ANY PARTICULAR PURPOSE. IN NO EVENT WILL AMD BE LIABLE TO ANY PERSON FOR ANY RELIANCE, DIRECT, INDIRECT, SPECIAL, OR OTHER CONSEQUENTIAL DAMAGES ARISING FROM THE USE OF ANY INFORMATION CONTAINED HEREIN, EVEN IF AMD IS EXPRESSLY ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. AMD, the AMD Arrow logo,

[insert all other AMD trademarks used in the material here per AMD Trademarks]

and combinations thereof are trademarks of Advanced Micro Devices, Inc. Other product names used in this publication are for identification purposes only and may be trademarks of their respective companies. 

[Insert any third party trademark attribution here per AMD's Third Party Trademark List.]©[Insert year written*]Advanced Micro Devices, Inc. All rights reserved.
