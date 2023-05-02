Local context is not enough! Towards Query Semantic and Knowledge Guided Multi-Span Medical Question Answering

Please follow the below setps to execute the experiments. 
	
	1. Install the dependencies provided in the environment.yml with the following commond.
	
		conda env create -f environment.yml
	
	2. To preprocess the data:

		sh scripts/prepro_sentqa.sh
	
	3. To run the models
		
		sh scripts/sentqa_GPU.sh
		

Package dependencies 

  - _libgcc_mutex=0.1=main
  - _openmp_mutex=5.1=1_gnu
  - _tflow_select=2.1.0=gpu
  - absl-py=0.15.0=pyhd3eb1b0_0
  - astor=0.8.1=py37h06a4308_0
  - blas=1.0=mkl
  - c-ares=1.18.1=h7f8727e_0
  - ca-certificates=2022.4.26=h06a4308_0
  - cached-property=1.5.2=py_0
  - certifi=2022.5.18.1=py37h06a4308_0
  - cudatoolkit=10.0.130=0
  - cudnn=7.6.5=cuda10.0_0
  - cupti=10.0.130=0
  - gast=0.2.2=py37_0
  - google-pasta=0.2.0=pyhd3eb1b0_0
  - grpcio=1.42.0=py37hce63b2e_0
  - h5py=3.6.0=py37ha0f2276_0
  - hdf5=1.10.6=hb1b8bf9_0
  - importlib-metadata=4.11.3=py37h06a4308_0
  - intel-openmp=2022.0.1=h06a4308_3633
  - keras-applications=1.0.8=py_1
  - keras-preprocessing=1.1.2=pyhd3eb1b0_0
  - ld_impl_linux-64=2.38=h1181459_1
  - libffi=3.3=he6710b0_2
  - libgcc-ng=11.2.0=h1234567_1
  - libgfortran-ng=7.5.0=ha8ba4b0_17
  - libgfortran4=7.5.0=ha8ba4b0_17
  - libgomp=11.2.0=h1234567_1
  - libprotobuf=3.20.1=h4ff587b_0
  - libstdcxx-ng=11.2.0=h1234567_1
  - markdown=3.3.4=py37h06a4308_0
  - mkl=2020.2=256
  - mkl-service=2.3.0=py37he8ac12f_0
  - mkl_fft=1.3.0=py37h54f3939_0
  - mkl_random=1.1.1=py37h0573a6f_0
  - ncurses=6.3=h7f8727e_2
  - numpy=1.19.2=py37h54aff64_0
  - numpy-base=1.19.2=py37hfa32c7d_0
  - openssl=1.1.1o=h7f8727e_0
  - opt_einsum=3.3.0=pyhd3eb1b0_1
  - pip=21.2.2=py37h06a4308_0
  - protobuf=3.20.1=py37h295c915_0
  - python=3.7.13=h12debd9_0
  - readline=8.1.2=h7f8727e_1
  - scipy=1.6.2=py37h91f5cce_0
  - sentencepiece=0.1.95=py37hd09550d_0
  - setuptools=61.2.0=py37h06a4308_0
  - six=1.16.0=pyhd3eb1b0_1
  - sqlite=3.38.3=hc218d9a_0
  - tensorboard=1.15.0=pyhb230dea_0
  - tensorflow=1.15.0=gpu_py37h0f0df58_0
  - tensorflow-base=1.15.0=gpu_py37h9dcbed7_0
  - tensorflow-estimator=1.15.1=pyh2649769_0
  - tensorflow-gpu=1.15.0=h0d30ee6_0
  - termcolor=1.1.0=py37h06a4308_1
  - tk=8.6.12=h1ccaba5_0
  - typing_extensions=4.1.1=pyh06a4308_0
  - webencodings=0.5.1=py37_1
  - werkzeug=0.16.1=py_0
  - wheel=0.37.1=pyhd3eb1b0_0
  - wrapt=1.13.3=py37h7f8727e_2
  - xz=5.2.5=h7f8727e_1
  - zipp=3.8.0=py37h06a4308_0
  - zlib=1.2.12=h7f8727e_2



