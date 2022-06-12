docker_image(
    name="test",
    instructions=[
        "FROM busybox",
        "COPY foo /",
    ],
    skip_push=True,
    dependencies=[
        "src/python/proj_a:dist",
        "src/python/proj_b:dist",
    ],
)
