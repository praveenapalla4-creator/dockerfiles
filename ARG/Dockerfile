ARG VERSION
# almalinux 9 ver use chesthunamm if futurer lo 10 or any othervresion kabalane mali file ki 
#vachi edit cheyyali push chesi pull cheyyali. so ala chyyakunda VERSION var istham if vers valu ivvakapothe default 9 teesukuntundhi
FROM almalinux:${VERSION:-9} 
ARG COURSE="DOCKER"\
    TRAINER="SIVAKUMAR"
#build time lo pampe argument ni contaniner lo acess chesukovataniki ENV use chesam
# ENV COURSE={COURSE} 
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}, Version: ${VERSION}"
#from ki mundhu ichina arg container lo access cheyylemu means when we build this we get the values of TRAINER COURSE but we can access the value of VERSION
CMD ["sleep", "1000"]