FROM devkitpro/devkita64:20190720

RUN dkp-pacman -Syu libnx --noconfirm
RUN dkp-pacman -Scc --noconfirm

WORKDIR /developer/components/NX-Shell

ENTRYPOINT ["make", "-j8"]
