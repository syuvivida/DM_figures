# Conclusion
The difference between 5F and 4F is smaller compared to the difference between NNPDF 3.1 and 3.0.
Different versions give different rapidity and pz distributions.

The distributions from "5F PDFs + 4F cards" vs "5F PDFs + 5F cards" are also consistent with each other.

Naming:

263000 NNPDF 3.0 5F LO PDFs
263400 NNPDF 3.0 4F LO PDFs
315200 NNPDF 3.1 5F LO PDFs
5F_315200 NNPDF 3.1 5F LO PDFs with consistent pro card and run card
263400_315200 use the weights saved in samples with default PDF=315200 to get 263400 distributions


all.pdf: compared all configurations above

263400_job_ZpBaryonic_MZp5000_MChi1_test263400_315200_job_ZpBaryonic_MZp5000_MChi1.pdf: compare samples with 263400 as default vs the distributions weighted with 263400 PDF weights (default is 315200)


263000_job_ZpBaryonic_MZp5000_MChi1_263400_job_ZpBaryonic_MZp5000_MChi1.pdf: 5F vs 4F for the same NNPDF 3.0 
263000_job_ZpBaryonic_MZp5000_MChi1_315200_job_ZpBaryonic_MZp5000_MChi1.pdf: 5F only, compare NNPDF versions
263400_job_ZpBaryonic_MZp5000_MChi1_315200_job_ZpBaryonic_MZp5000_MChi1.pdf: 2015/2016 MC setting vs 2017/2018 setting
315200_job_ZpBaryonic_MZp5000_MChi1_5F_job_ZpBaryonic_MZp5000_MChi1.pdf: 315200 PDF but with 4F vs 5F pro card/run card

## The configuration with non-physical distributions
315200_job_ZpBaryonic_MZp5000_MChi1_test315200_263400_job_ZpBaryonic_MZp5000_MChi1.pdf: compare samples with 315200 as default vs distributions weighted with 315200 PDF weights (default is 263400)
