install:
	$(MAKE) -C oauth install
	$(MAKE) -C ldap install

delete:
	$(MAKE) -C oauth delete
	$(MAKE) -C ldap delete

test:
	bundle install
	bundle exec rspec
