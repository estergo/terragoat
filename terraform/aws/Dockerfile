FROM python:3.7-slim
RUN apt install first_update_line \
&& apt update first_update_line
RUN apt update second_update_line
RUN apt update third_update_line
USER bob
ENV AWS_ACCESS_KEY_ID="wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY"
ENV AWS_SECRET_ACCESS_KEY="AKIAIOSFODNN7EXAMPLE"
