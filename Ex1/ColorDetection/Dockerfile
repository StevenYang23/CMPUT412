FROM duckietown/dt-duckiebot-interface:daffy-arm64v8
# use affy-arm32v7 daffy-arm64v8 if you are using a Duckiebot MOOC Founder's Edition

WORKDIR /color_detector_dir

COPY requirements.txt ./

COPY color_detector.py .

CMD python3 ./color_detector.py
