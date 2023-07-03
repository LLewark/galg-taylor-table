## What is this repository for?

This website lists the values of the algebraic genus [FL18] and the Taylor invariant [Tay77] for all prime knots with crossing number 12 or less.
Details about how these values were computed are contained in the papers [LM19, FL19].

> [FL18]  [_On classical upper bounds for slice genera_] by P. Feller and L. Lewark, Selecta Math. 24 (2018), no. 5, 4885–4916. MR3874707, Zbl 1404.57008, arXiv: 1611.02679.

> [Tay77] [_On the genera of knots_] by L. R. Taylor, In Topology of low-dimensional manifolds (Proc. Second Sussex Conf., Chelwood Gate, 1977), volume 722 of Lecture Notes in Math., pages 144–154. Springer, Berlin, 1979. MR0547461, Zbl 0409.57021.

> [FL19]  [_Balanced algebraic unknotting, linking forms, and surfaces in three- and four-space_] by P. Feller and L. Lewark, accepted in J. Differential Geom. arXiv:1905.08305.

> [LM19]  [_On calculating the slice genera of 11- and 12-crossing knots_] by L. Lewark and D. McCoy, Exp. Math. 28 (2019), no. 1, 81–94. MR3938580, Zbl 1414.57009, arXiv:1508.01098. 

The table is available here:
> [https://llewark.github.io/galg-taylor-table/](https://llewark.github.io/galg-taylor-table/).

## What are the other files for?

The table is generated from the source file `data.csv` by running the script `converter.py`:

    ./converter.py data.csv > index.html

This script is a modified copy of a script written by Claudius Zibrowius for a [similar online table](https://github.com/LLewark/theta).
