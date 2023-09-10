# learn-it-dev-with-diagrams
Learn IT development with diagrams.
Here you can find diagrammed instructions of various operations performed in order to develop IT applications.

These instructions are primarily intended for beginners. That is why I chose diagrams. They are of mermaid diagrams and look like this:
```mermaid
graph TD;
    A-->B;
    subgraph fast way
    B-->C;
    end
    A-->E;
    subgraph long way
    E-->F-->G;
    end
    C-->D;
    G-->B;
    F-->D;
    A(A novice encountered difficulty in development);
    B(The novice see a diagram);
    C(The novice quickly understands the principle);
    D(The novice solves the issue);
    E(The novice searches the internet);
    F(It takes a lot of time to find a solution);
    G(The solution doesn't sovle the issue);

    style D fill:#9FE2BF
```

You are welcome to contribute by finding a question in the issues section you have answer to. You pull request and I'll merge.


# License
This source code is licensed under the Creative Commons Attribution-NonCommercial-NoDerivs license (CC BY-NC-ND). You are free to view, read and share the code with others as long as you credit the author and provide appropriate attribution. Any modifications or commercial use are not permitted under this license. All rights are reserved by the author.
