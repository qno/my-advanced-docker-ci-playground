FROM ghcr.io/qno/my-advanced-docker-ci-playground-image-1 as image-1
FROM ghcr.io/qno/my-advanced-docker-ci-playground-image-2 as image-2

FROM alpine

COPY --from=image-1 image1.txt . 
COPY --from=image-2 image2.txt . 

CMD ["ls -la"]
