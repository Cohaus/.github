# 2024 Google Solution Challenge
![image](https://github.com/GDSC-C-E/.github/assets/116738827/ed812d4e-1b8b-4fe0-9ea2-6aac16f4783e)

---

# Cohaus
"Cohaus" is a platform that assist in improving living environment of vulnerable populations.
With Al-powered assistance, users can conveniently request repairs, and upon matching with volunteers, the platform facilitates both repair and waste disposal, creating a sustainable cycle.

---

## To Run Backend Application

1. Git Clone Backend Repository

2. Add application.yml at resources directory

3. Move to build/libs and execute the command
```
java -jar bsafe-0.0.1-SNAPSHOT.jar
```


## Dockerize ML with Tensorflow Serving
```
git clone https://github.com/GDSC-C-E/ML.git
```
```
docker run -it --rm -p 8500:8500 -p 8501:8501 -v "/home/gsc_gces/ML/:/models/cohaus" tensorflow/serving --model_name=cohaus_models --model_config_file=/models/cohaus/models.config --model_config_file_poll_wait_seconds=60
```
