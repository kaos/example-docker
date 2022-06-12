python_sources()
resources(name="files", sources=["README.md"])
python_distribution(
    name="dist",
    dependencies=[":files", ":proj_a"],
    provides=python_artifact(name="proj_a", version="1.0.0"),
)
