My name is Bruno Rodrigues and I’ve been using R and writing about it for a decade now. Maybe you’ve read some of my blog posts at www.brodrigues.co.

I’m raising money to package RStudio to Nix for macOS platforms.

# What is Nix?

Nix is a package manager that can be installed on Windows (through WSL2), Linux and macOS. If you’ve been using package manager on macOS, you
might be familiar with hombebrew. Nix is similar to homebrew but has fundamental differences. The biggest difference is that Nix puts a lot
of emphasis on reproducibility. Using Nix, it is possible to create isolated environments containing R, R packages and any other
tool needed to run an analysis. It is possible to even install older versions of R and R packages to reproduce older studies.
Software insalled with Nix lives alongside the software you install through other means on your computer, meaning that using Nix it is possible
to have several development environments, each containing its own version of R and R packages, and use one complete environment per project.

The Nix package manager has existed for 20 years and currently contains more than 80'000 software packages, including the entirety of CRAN
and Bioconductor.

# What is RStudio?

RStudio is a very popular development environment for the R programming language developed by Posit. RStudio is available for Windows, Linux
and macOS, and can be installed through the usual means. But it is also possible to install RStudio through the Nix package manager, but only
for Windows and Linux. Environments built using Nix cannot be "seen" by versions of RStudio installed through the usual methods of your 
operating system: this means that on macOS, if could not develop on such an environment using RStudio.

# How much mony is needed and why?

I am not a macOS user, but believe that everyone could benefit if RStudio was packaged for macOS platforms. I thus contacted a company
called Numtide which offers a Nix packaging service: https://nix-packaging.com/. Essentially, you pay them, and they package software
for the Nix package manager. After discussing with them, they offered porting RStudio for macOS for USD4500. This fundraiser is thus
EUR4500 which translates to more than USD4500. The difference is to cover for exchange rate risk and Gofundme fees. I will donate
the remainder to the R foundation. I will provide all the contracts, proofs and bank receipts as proof that the money went where it went.

# Why should we trust you?

As I said in the beginning, I’ve been using R and writing about it for a decade now. I consider myself a member of the R community,
and have discovered Nix fairly recently. I also contribute to R itself, through three packages that I’ve written (chronicler and michelRodange 
on CRAN, rix soon to be released on CRAN). I’m putting my reputation on the line, for what it’s worth, and am fortunate enough to not need
to steal from the community.

# What if the goal is not met?

If the goal is not met until the end of the year, I will donate all the money (minus fees) to the R foundation.
