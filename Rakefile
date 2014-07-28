require 'cloudformer/tasks'

Cloudformer::Tasks.new("vpn") do |t|
  t.template = "cloudformation.json"
  t.parameters = {"AmiId" => "ami-7c807d14"}
  t.disable_rollback = true
  t.capabilities=[]
end
