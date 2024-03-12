# Cohaus
> 2024 Google Solution Challenge </br>
> _Gachon Univ._

"Cohaus" is a platform that assist in improving living environment of vulnerable populations. </br>
With Al-powered assistance, users can conveniently request repairs, and upon matching with volunteers, the platform facilitates both repair and waste disposal, creating a sustainable cycle.

![image](https://github.com/GDSC-C-E/.github/assets/116738827/ed812d4e-1b8b-4fe0-9ea2-6aac16f4783e)

---

### Demo Video (on Youtube)
https://youtu.be/tiJGJ4WtB5k

---

# Main Feature
![1](https://github.com/Cohaus/.github/assets/116738827/5e20e564-7e6a-4772-bd36-4281e2c09768)

![2](https://github.com/Cohaus/.github/assets/116738827/3c40dfef-9282-4f3b-9a67-d8f8afc534d6)

![3](https://github.com/Cohaus/.github/assets/116738827/e44b2705-0c1b-4777-9a59-c0006bd57d84)

![4](https://github.com/Cohaus/.github/assets/116738827/e676547c-908e-4554-9a18-4463304eb79f)

![5](https://github.com/Cohaus/.github/assets/116738827/a3a0e358-2939-437e-959e-4854f70af72e)

---

# Getting Started
### Run Android Application

1. Git clone mobile repository

2. Run Android Studio and open it

3. Add the emulator and run it
```
git clone https://github.com/GDSC-C-E/Mobile.git
```

### Run Backend Application

1. Git Clone Backend Repository

2. Add application.yml at resources directory

3. Move to build/libs and execute the command
```
java -jar bsafe-0.0.1-SNAPSHOT.jar
```

### Dockerize ML with Tensorflow Serving
```
git clone https://github.com/GDSC-C-E/ML.git
```
```
docker run -it --rm -p 8500:8500 -p 8501:8501 -v "/home/gsc_gces/ML/:/models/cohaus" tensorflow/serving --model_name=cohaus_models --model_config_file=/models/cohaus/models.config --model_config_file_poll_wait_seconds=60
```

---

# Team Member

| Kim Jiwon  | Seo Juwon      | Jang Minsu | Jung Gunoh |
|------------|----------------|------------|------------|
| ![7f086f54a](https://github.com/GDSC-C-E/.github/assets/116738827/31728d59-43d5-434b-918a-2d74bbebdd0b) | ![46197bbbf](https://github.com/GDSC-C-E/.github/assets/116738827/d096222e-ce70-4431-b3cf-702801598763) | ![62dbd50a4 (1)](https://github.com/GDSC-C-E/.github/assets/116738827/2cb70ac3-c223-4883-8297-630e404611c2) | ![a9c393e97](https://github.com/GDSC-C-E/.github/assets/116738827/32735f73-78e7-4707-b5a5-3773be9f7e24) |
| Backend/PM | Backend/Design | Mobile     | AI         |
| [@kiwijomn](https://github.com/kiwijomn) | [@joowojr](https://github.com/joowojr) | [@Tnalxmsk](https://github.com/Tnalxmsk) | [@99NO](https://github.com/99NO) |
