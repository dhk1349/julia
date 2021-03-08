# Julia tutorial

Tutorial of Julia for myself



## Installation

> #### 1. Install release file.
>
> https://julialang.org/downloads/#musl-fn
>
> For me, I downloaded "Generic Linux on x86 64-bit(GPG)"



> #### 2. Unzip downloaded file.
>
> tar -xvzf -xvzf julia-1.5.3-linux-x86_64.tar.gz 



> #### 3. Copy unzipped file to /opt/
>
> sudo cp -r julia-1.5.3 /opt/



> #### 4. Create symbolic link to julia inside to /usr/bin/local/bin
>
> sudo ln -s /opt/julia-1.5.3/bin/julia /usr/local/bin/julia



> #### 5. Execute julia on CLI.
>
> julia