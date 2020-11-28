# TamelyUtilities

# What can you do with this?

# With this dll you can do several things:

# You can Convert items:

# Usage: 
C#
using TamelyUtilities;

Utilities.Convert(String you are searching for, string you are replacing, pak you are replacing in, offset for the replace);


The pak needs to be the file path and the offset can be a researcher offset (i.e. 0 or 1000000).


# You can Revert items

# Usage: 
C#
using TamelyUtilities;

Utilities.Revert(String you are searching for, string you are replacing, pak you are replacing in, offset for the replace);


The pak needs to be the file path and the offset can be a researcher offset (i.e. 0 or 1000000).


# You can get the Pak Path

# Usage: 
C#
using TamelyUtilities;

Utilities.GetPakPath();



# You can pull offsets from my API

# Usage: 
C#
using TamelyUtilities;

Utilities.GetFemaleBody(); or Utilities.GetFemaleGender(); or Utilities.GetFemaleHead(); or Utilities.GetMaleBody(); or Utilities.GetMaleGender(); or Utilities.GetMaleHead(); or Utilities.GetBackbling(); or Utilities.GetPickaxe(); or Utilities.GetGlider();


Change all of those to longs you want the offset saving to.


# Hope you enjoy it! Please let me know if there is anything else I can add to it to make it easier/more user friendly for you!
