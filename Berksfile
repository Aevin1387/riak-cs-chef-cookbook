source "https://supermarket.getchef.com"

metadata

group :integration do
  cookbook "apt"
  cookbook "yum"
  cookbook "sudo"
  cookbook "minitest-handler"
  cookbook "packagecloud"

  cookbook "riak", git: "git@github.com:Aevin1387/riak-chef-cookbook.git", branch: "refactor"
  cookbook "riak-cs-create-admin-user", github: "shaon/chef-riak-cs-create-admin-user"
  cookbook "riak-cs-ssl", github: "shaon/chef-riak-cs-ssl"
end
