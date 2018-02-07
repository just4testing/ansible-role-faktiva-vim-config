# Ansible Role tests

To run the test playbook(s) in this directory:

  1. Install and start Docker.
  2. Download the test shim (see .travis.yml file for the URL) into `tests/test.sh`:
    - `wget -O tests/test.sh https://gist.githubusercontent.com/drAlberT/3749100d13f4143508d56aa5b1ae23ad/raw`
  3. Make the test shim executable: `chmod +x tests/test.sh`.
  4. Run (from the role root directory) `distro=[distro] playbook=[playbook] ./tests/test.sh`

If you don't want the container to be automatically deleted after the test playbook is run, add the following environment variables: `cleanup=false`
