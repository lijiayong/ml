# ml
## Wavenet references
- [buriburisuri/speech-to-text-wavenet: Speech-to-Text-WaveNet : End-to-end sentence level English speech recognition based on DeepMind's WaveNet and tensorflow](https://github.com/buriburisuri/speech-to-text-wavenet): sugartensor
- [tomlepaine/fast-wavenet: Efficient implementation of Wavenet generation.](https://github.com/tomlepaine/fast-wavenet): mostly concerned with efficiency
- [ibab/tensorflow-wavenet: A TensorFlow implementation of DeepMind's WaveNet paper](https://github.com/ibab/tensorflow-wavenet): most vanilla, probably

## Tensorflow installation on the cluster
### Installing the libraries
[python - Error while importing Tensorflow in python2.7 in Ubuntu 12.04. 'GLIBC_2.17 not found' - Stack Overflow](http://stackoverflow.com/questions/33655731/error-while-importing-tensorflow-in-python2-7-in-ubuntu-12-04-glibc-2-17-not-f/34897674#34897674)

### Commands to load

```
module load anaconda
source activate tensorflow
python-libc

### Mount the folder
Use `sshfs -o follow_symlinks $user@$server:$folder $mountpount` to follow symlinks
