---
layout: post
title:  "Member Variables Naming"
---

### Rule

We decided to homogenize member variables in our source code. The rule is to use a 'm' prefix then variable name with possibly several words starting with uppercase like this :

`int mVariableName;`

For CoreModifiable attributes, the rule is to have the acces key of the attribute match the variable name :

`maFloat					mThreshold = BASE_ATTRIBUTE(Threshold, 0.0f);
maString				mTextureName = BASE_ATTRIBUTE(TextureName, "");`

This way, the KigsDocs and Doxygen tools can treat those attributes in a specific way. 

### Huge renamming pass
 
 A lot of source code was amended to follow this rule. More changes to come to add comments in our code and so improve code readability and generated docs with Doxygen.  



 

