FROM archlinux:latest

RUN pacman -Syu --noconfirm && \
    pacman -S --noconfirm distcc gcc clang && \
    pacman -Scc --noconfirm

ENTRYPOINT ["distccd", "--no-detach", "--log-level=info", "--log-stderr"]
