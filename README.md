# OpenPseudonymizer

OpenPseudonymiser is Copyright Julia Hippisley-Cox, University of Nottingham 2011

OpenPseudonymiser is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

OpenPseudonymiser, including the website, software, documentation and key server technology, is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](http://www.gnu.org/licenses/) for more details.

Organisations who wish to make use of the Open Pseudonymiser technology have full responsibility for regarding information governance and security considerations relevant to their purposes. The Key Server on this website is intended for demonstration purposes only. Organisations wishing to use Open Pseudonymiser for production purposes should deploy an instance of the software/key server etc suitable for their own purposes in order to satisfy their own information governance and security requirements.

Please see the following document entitled "Anonymisation: managing data protection risk code of practice" (https://ico.org.uk/media/1061/anonymisation-code.pdf)
The case study on page 79 has an example of using the cryptographic hash technique.

The DLL and JAVA libraries are released under the GNU Lesser Public License 3 (http://www.gnu.org/licenses/lgpl.html)

The University of Nottingham thanks QResearch (www.qresearch.org) for contributing to the cost of developing this software.

OpenPseudonymiser makes use of the following Open Source libraries:
- RSAEncryption Class Version 1.00 which is Copyright (c) 2009 Dudi Bedner (http://www.codeproject.com/KB/security/PrivateEncryption.aspx)
- BigInteger Class Version 1.03 which is Copyright (c) 2002 Chew Keong TAN (http://www.codeproject.com/KB/cs/biginteger.aspx)
- The NHSNumber validation code is based on an Open Source work by Peter Fisher. The original NHSNumber validation code can be found on here on GitHub (https://github.com/pfwd/NHSNumber-Validation)

## Build
You need Java v1.5 or higher.
Compile and test by running:
  ant
at the command prompt.
