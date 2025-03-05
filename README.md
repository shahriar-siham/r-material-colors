<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/shahriar-siham/r-material-colors/blob/main/image/material-design-logo-light.svg" width="100" height="100">
  <img src="https://github.com/shahriar-siham/r-material-colors/blob/main/image/material-design-logo.svg" width="100" height="100">
</picture>

# Material Design Colors for R

As a graphic designer, I just couldn't vibe with the default colors R gives you for plotting.  They're... fine, I guess? But they lack that modern, polished look.  So I thought, why not use Google's <a href = "https://api.flutter.dev/flutter/material/Colors-class.html"> Material Design Colors</a> instead?  

Now you can bring that clean, aesthetic Material Design palette into your R plots effortlessly.  

## Installation

You can install the package from GitHub using the `devtools` package:

```R
# Install devtools if not already installed
install.packages("devtools")

# Install materialColors from GitHub
devtools::install_github("shahriar-siham/r-material-colors")
```

## Example

```R
library(materialColors)

mcolor("blue") # Returns hex code for blue color, shade 500
mcolor("blue_accent", 200) # Returns hex code for blue accent, shade 200
mcolor("red", 1000) # Returns NA and prints a warning
```

## License

This package is licensed under the MIT License.