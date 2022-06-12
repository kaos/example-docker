python_sources()
resources(name="files", sources=["README.md"])
python_distribution(
    name="dist",
    dependencies=[":files", ":proj_b"],
    provides=python_artifact(name="proj_b", version="2.0.0"),
)
