# LEDAbioinfo
Lugar para guardar informações referente a Bioinfo dos membros do LEDAlab.


--------------------------------------------------------------------------

# Utilizar Ubuntu (Linux) no Windows:

Siga os passos abixo para poder utilizar o cmd do Ubuntu pelo Windows.

Painel de conrole;

Proramas;

Ativar ou desativar recursos do Windows;

Ativar subsitema do Windows para Linux;

Reiniciar PC;

Baixar na Microsoft Store o Ubuntu.

--------------------------------------------------------------------------

# Baixar SRA Toolkit:

wget http://ftp-trace.ncbi.nlm.nih.gov/sra/sdk/3.0.2/sratoolkit.3.0.2-ubuntu64.tar.gz

# Descompatar o SRA Toolkit: 

tar -xvzf sratoolkit.3.0.2-ubuntu64.tar.gz

# Baixndo uma sequencia do NCBI com SRA:

/home/nome_do_usuário/sratoolkit.3.0.2-ubuntu64/bin/fastq-dump --split-files --gzip SRR000000(codigo no NCBI)

--------------------------------------------------------------------------

# Baixar o FastQC:

wget http://www.bioinformatics.babraham.ac.uk/projects/fastqc/fastqc_v0.12.1.zipwget

# Descompactação do arquivo FastQC(zip):

unzip fastqc_v0.12.1.zip

# Rodar FastQC:

/home/nome_do_usuáio/FastQC/fastqc SRR000000_1.fastq.gz

# Para rodar tem que instalar o Java!!
--------------------------------------------------------------------------
