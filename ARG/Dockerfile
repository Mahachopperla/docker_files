ARG version
FROM almalinux:${version:-9}
ENV COURSE="Devops" \
      DURATION="120HRS" 
ARG TRAINER="siva"
ENV TRAINER=${TRAINER}
RUN echo "Hi! course is ${COURSE}, duration is ${DURATION}, Trainer is ${TRAINER}"
CMD ["sleep", "1000"]
